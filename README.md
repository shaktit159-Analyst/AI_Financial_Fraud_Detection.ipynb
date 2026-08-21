# 🔐 AI-Powered Financial Fraud Detection System

### Machine Learning + NLP Based Fraud Detection Project

An end-to-end financial fraud detection system that uses **Machine Learning and Natural Language Processing (NLP)** to identify potentially fraudulent financial transactions.

---

## 📌 Project Overview

Financial fraud is a major challenge for digital payment and banking systems. This project demonstrates how Machine Learning and NLP can be combined to analyze transaction information and identify suspicious transactions.

The system analyzes multiple transaction attributes such as:

- 💰 Transaction Amount
- 🕐 Transaction Time
- 🌍 Transaction Location
- 💻 Device Information
- 🏦 Account History
- 🔄 Transaction Type
- ⚠️ Failed Attempts
- 📱 New Device Information
- 📝 Transaction Description

The project follows an end-to-end Machine Learning workflow, starting from data exploration and preprocessing and continuing through model training, evaluation, and fraud prediction.

> **Note:** The dataset used in this project is simulated and created for educational/prototype purposes. It does not represent real banking or customer data.

---

## 🎯 Project Objectives

The main objectives of this project are:

1. Understand and explore financial transaction data.
2. Perform Exploratory Data Analysis (EDA).
3. Preprocess numerical, categorical, and text-based data.
4. Apply NLP techniques to transaction descriptions.
5. Train Machine Learning models for fraud detection.
6. Compare model performance using evaluation metrics.
7. Select an appropriate model for fraud prediction.
8. Demonstrate prediction on new transaction data.

---

## 📊 Dataset

The project uses a **simulated financial transaction dataset** containing approximately 10,000 transactions.

### Important Features

| Feature | Description |
|---|---|
| Transaction Amount | Monetary value of the transaction |
| Transaction Hour | Hour at which the transaction occurred |
| International | Indicates an international transaction |
| Previous Transactions | Previous transaction history |
| Account Age | Age/history of the account |
| Failed Attempts | Number of failed transaction attempts |
| New Device | Indicates whether a new device was used |
| Transaction Type | Type of financial transaction |
| Location | Transaction location |
| Device | Device/platform used |
| Description | Text description of the transaction |
| Fraud | Target variable indicating fraudulent activity |

### Target Variable

- `0` → Legitimate Transaction
- `1` → Fraudulent Transaction

---

## 🔍 Exploratory Data Analysis (EDA)

Before training the models, the transaction data was explored to understand important patterns.

EDA included analysis of:

- Fraud vs. legitimate transactions
- Transaction amount distribution
- Transaction timing
- Transaction patterns
- Fraud-related feature relationships
- Data quality and missing values

Visualizations were used to make the patterns easier to understand.

---

## 🧹 Data Preprocessing

Different preprocessing techniques were applied according to the type of data.

### Numerical Features

Numerical features were standardized using a scaler so that features with different ranges could be handled effectively by Machine Learning algorithms.

### Categorical Features

Categorical variables such as transaction type, location, and device were converted into numerical representations using encoding techniques.

### Text Features

Transaction descriptions contain useful textual information.

NLP preprocessing was performed and **TF-IDF (Term Frequency–Inverse Document Frequency)** was used to convert transaction descriptions into numerical features.

---

## 🧠 Machine Learning Models

Multiple Machine Learning algorithms were trained and compared for fraud classification.

### 🌲 Random Forest

Random Forest combines multiple decision trees to improve prediction performance and robustness.

### 🌳 Decision Tree

Decision Tree makes predictions using a sequence of decision rules based on transaction features.

### 👥 K-Nearest Neighbors (KNN)

KNN predicts a transaction based on the similarity between the transaction and nearby observations in the feature space.

---

## 🔗 Feature Engineering

The project combines different types of information:

```text
Numerical Features
        +
Categorical Features
        +
NLP / TF-IDF Features
        ↓
Final Feature Set
        ↓
Machine Learning Model
        ↓
Fraud Prediction

##AUTHOR
SHAKTI SINGH TOMAR
