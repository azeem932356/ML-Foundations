# Introduction to Machine Learning

## What is Machine Learning?

Machine Learning (ML) is the process of training a piece of software, called a **model**, to make useful predictions or generate content.

Instead of explicitly programming rules, models learn patterns from data.

---

# Types of Machine Learning

## 1. Supervised Learning

Supervised learning uses **labelled data**, where the correct answers are already known.

The model learns the relationship between inputs (**features**) and outputs (**labels**) to make predictions on unseen data.

### Types of Supervised Learning

#### Regression
Regression predicts **numerical values**.

Examples:
- House price prediction
- Temperature prediction
- Rainfall prediction

Example outputs:
- ₹50,00,000
- 35°C
- 120 mm rainfall

#### Classification

Classification predicts categories or classes.

Examples:
- Spam or Not Spam
- Fraud or Not Fraud
- Disease or No Disease

##### Binary Classification
Only two possible outputs:

- Yes / No
- True / False
- Spam / Not Spam

##### Multiclass Classification
More than two possible outputs:

- Cat
- Dog
- Bird
- Horse

---

## 2. Unsupervised Learning

Unsupervised learning works with **unlabelled data**.

The model attempts to discover hidden patterns or relationships in the data.

The most common technique is **clustering**, which groups similar data points into clusters.

Examples:
- Customer segmentation
- Product recommendation
- Grouping similar documents

---

## 3. Reinforcement Learning

Reinforcement Learning learns by interacting with an environment.

The model receives:

- Rewards for good actions
- Penalties for bad actions

Examples:
- Robot training
- Self-driving cars
- Chess playing AI

---

## 4. Generative AI

Generative AI creates new content based on user input.

Examples:
- Text generation
- Image generation
- Code generation
- Music generation

---

# Supervised Learning Concepts

## 1. Data

Data is the driving force of Machine Learning.

Data can exist as:

- Tables
- Images
- Audio files
- Videos
- Text

Datasets consist of individual examples containing:

### Features
Features are input variables used by a model to make predictions.

### Labels
Labels are the correct answers that the model tries to predict.

### Rainfall Example

| Date | Latitude | Longitude | Temperature | Humidity | Cloud Coverage | Rainfall |
|------|----------|-----------|-------------|----------|---------------|----------|
| 01-07-2026 | 12.97 | 77.59 | 29°C | 85% | High | 15 mm |

Features:
- Date
- Latitude
- Longitude
- Temperature
- Humidity
- Cloud Coverage

Label:
- Rainfall

---

## 2. Model

A model is a mathematical representation that learns relationships between features and labels.

The model discovers these relationships during training.

---

## 3. Training

Training is the process of showing labelled data to a model so that it can learn patterns.

Input:

Features + Labels

Output:

Trained Model

---

## 4. Evaluation

Evaluation measures how well a model has learned.

### Step 1: Provide feature values

| Temperature | Humidity | Cloud Coverage | Actual Rainfall |
|------------|----------|---------------|----------------|
| 28°C | 82% | High | 20 mm |

### Step 2: Model prediction

Predicted Rainfall = 18 mm

### Step 3: Compare prediction with actual value

Actual Rainfall = 20 mm

Prediction Error = 2 mm

If performance is poor:

- Improve data quality
- Tune model parameters
- Train again

This cycle continues until acceptable performance is achieved.

---

## 5. Inference

Once evaluation results are satisfactory, the model is deployed.

Using the trained model to make predictions on new unseen data is called **Inference**.

Example:

Input:
- Temperature = 31°C
- Humidity = 88%
- Cloud Coverage = High

Output:
- Predicted Rainfall = 25 mm

---

# Complete Machine Learning Workflow

Data
↓
Model
↓
Training
↓
Evaluation
↓
Inference
↓
Deployment




---

# Source

These notes were created while studying the Google Machine Learning Crash Course.

Course:
Google ML Crash Course - Introduction to Machine Learning and Codebasics ML course on YouTube

Link:
https://developers.google.com/machine-learning/intro-to-ml/understanding
https://www.youtube.com/playlist?list=PLeo1K3hjS3uvCeTYTeyfe0-rN5r8zn9rw
