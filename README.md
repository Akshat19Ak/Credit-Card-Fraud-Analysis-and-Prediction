# Credit-Card-Fraud-Analysis-and-Prediction

An end-to-end Jupyter Notebook project that downloads a credit card fraud dataset, performs detailed exploratory data analysis (EDA), preprocesses the data, trains a Random Forest model to detect fraudulent transactions, and examines when fraud occurs.

## Project Overview

- **Purpose:**  
  - Detect fraudulent credit card transactions using real-world data.
  - Gain insights on transaction patterns and the timing of fraud events.

- **Key Steps:**  
  - **Data Collection:** Download and unzip the dataset from Kaggle.
  - **Exploratory Data Analysis (EDA):**  
    - Review dataset shape, types, and summary statistics.
    - Check for missing values.
    - Visualize class distribution, feature distributions, correlations, and outliers.
  - **Preprocessing:**  
    - Standardize key features ('Amount' and 'Time') to normalize data.
    - Remove the original columns after scaling.
  - **Modeling:**  
    - Split data into training and testing sets (keeping class imbalance intact).
    - Train a Random Forest classifier to predict fraud.
  - **Evaluation:**  
    - Generate a classification report, confusion matrix, and ROC curve.
  - **Fraud Timing Analysis:**  
    - Combine predictions with original time values.
    - Visualize when fraudulent transactions are predicted and their frequency over time.

---

## Installation and Requirements

- **Python 3.7+**
- **Jupyter Notebook** (or JupyterLab)
- **Kaggle API:** Set up `kaggle.json` in the appropriate directory.
- **Required Libraries:**  
  - pandas, numpy, matplotlib, seaborn, scikit-learn  
  *(Install via `pip install pandas numpy matplotlib seaborn scikit-learn`)*

---

## How to Run

- Open the provided Jupyter Notebook.
- Execute each cell sequentially:
  - Start with importing libraries.
  - Download and load the dataset.
  - Perform EDA, preprocess data, split the dataset.
  - Train and evaluate the model.
  - (Optional) Run the additional cell for fraud timing analysis.
- No code changes are necessary; just run the cells as provided.

---

## What You’ll See

- **Data Exploration:**  
  - Visual summaries of dataset details and distributions.
  - Clear plots showing the imbalance between normal and fraudulent transactions.
- **Model Training:**  
  - A Random Forest classifier that learns to distinguish fraud.
- **Model Evaluation:**  
  - Performance metrics including precision, recall, ROC AUC.
- **Fraud Timing:**  
  - Graphs displaying when frauds are predicted to occur and how often.

---

## Final Notes

- The dataset is highly imbalanced (fraud cases are very rare) which reflects real-world conditions.
- This project walks you through every step—from data collection to prediction—making it easy to follow and learn.
- Use the visualizations and printed summaries to understand the model’s predictions and the underlying data patterns.

---
