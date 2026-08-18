# AI Financial Fraud Detection

An end-to-end Machine Learning project for detecting potentially fraudulent financial transactions using transaction features and Natural Language Processing (NLP).

## Project Overview

This project demonstrates a complete financial fraud detection workflow using Python, Machine Learning, and NLP.

The system analyzes transaction information such as:

- Transaction amount
- Transaction hour
- International transaction status
- Previous transaction history
- Account age
- Failed attempts
- New device information
- Transaction type
- Location
- Device
- Transaction description

A **Random Forest Classifier** is trained to classify transactions as legitimate or potentially fraudulent.

> **Note:** The dataset used in this project is simulated and created for educational purposes. The results should not be interpreted as real-world banking performance.

## Technologies Used

- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- Scikit-learn
- Joblib
- Jupyter Notebook
- TF-IDF
- Random Forest

## Project Workflow

1. Create a simulated financial transaction dataset
2. Understand the dataset
3. Perform Exploratory Data Analysis (EDA)
4. Split data into training and testing sets
5. Clean transaction text
6. Convert text into numerical features using TF-IDF
7. Scale numerical features
8. Encode categorical features
9. Combine all feature groups
10. Train a Random Forest classifier
11. Evaluate model performance
12. Analyze the confusion matrix
13. Analyze feature importance
14. Test suspicious and legitimate transactions
15. Save the trained model and preprocessing objects

## Machine Learning Model

The project uses a **Random Forest Classifier** with:

- 200 decision trees
- Maximum tree depth of 15
- Balanced class weights
- Fixed random state for reproducibility

## Model Evaluation

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Classification Report
- Confusion Matrix

## NLP Component

Transaction descriptions are processed using **TF-IDF (Term Frequency-Inverse Document Frequency)**.

The text vectorizer is fitted only on the training data to help prevent data leakage.

## Example Predictions

The notebook demonstrates two example transactions:

### Suspicious Transaction

A high-value international transaction made from a new device with multiple failed attempts and a suspicious description.

### Legitimate Transaction

A routine purchase with normal transaction characteristics.

## Saved Model Files

The project saves the following Machine Learning artifacts:

- `fraud_detection_model.pkl`
- `transaction_text_vectorizer.pkl`
- `transaction_scaler.pkl`
- `transaction_encoder.pkl`

These files allow the trained model and preprocessing steps to be reused later.

## Limitations

This is an educational Machine Learning project based on simulated data.

A production-level fraud detection system would require:

- A representative real-world dataset
- Proper handling of class imbalance
- Cross-validation
- Hyperparameter tuning
- Robust security and privacy controls
- Real-time monitoring
- Extensive validation on unseen data
- Domain-specific fraud investigation

## Future Scope

Possible future improvements include:

- Using a real public fraud detection dataset
- Comparing multiple Machine Learning algorithms
- Hyperparameter optimization
- Advanced class-imbalance techniques
- Real-time fraud detection
- Web application deployment
- Explainable AI
- Cloud deployment

##AUTHOR

Shakti singh tomar

This project was created for learning and demonstrating practical Machine Learning, NLP, and fraud detection concepts.
