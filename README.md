# Logistic Regression - Classification

## 📌 Project Overview

This project demonstrates the implementation of **Logistic Regression**, a supervised machine learning algorithm used primarily for **binary classification** problems.

The model learns the relationship between input features and a target variable and predicts the probability of an observation belonging to a particular class.

---

## 🎯 Objective

The main objectives of this project are:

- Understand Logistic Regression
- Perform data preprocessing and cleaning
- Split the dataset into training and testing sets
- Train a Logistic Regression model
- Make predictions using the trained model
- Evaluate model performance using classification metrics
- Analyze the model using a ROC curve and AUC score

---

## 🧠 What is Logistic Regression?

Logistic Regression is a **supervised classification algorithm** that predicts the probability of an outcome belonging to a particular class.

Unlike Linear Regression, which predicts continuous values, Logistic Regression is commonly used when the target variable contains categories such as:

- 0 / 1
- Yes / No
- Pass / Fail
- Positive / Negative

The model uses the **sigmoid function** to convert the predicted value into a probability between 0 and 1.

### Sigmoid Function

```text
P(y = 1) = 1 / (1 + e^(-z))
