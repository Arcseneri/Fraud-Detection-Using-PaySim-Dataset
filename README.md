# Fraud Detection Using PaySim Dataset

## Project Overview

This project analyzes fraudulent financial transactions using the PaySim dataset, a synthetic dataset designed to simulate real-world mobile banking transactions. The objective is to identify fraud patterns, understand transaction behaviors associated with fraudulent activities, and build machine learning models capable of detecting suspicious transactions.

The project includes data exploration, preprocessing, feature engineering, machine learning modeling, and model evaluation. Logistic Regression and Random Forest were implemented and compared to assess their effectiveness in fraud detection.

---

## Project Objectives

* Analyze transaction patterns associated with fraudulent activities.
* Identify high-risk transaction types and suspicious balance behaviors.
* Build and evaluate machine learning models for fraud detection.
* Compare the performance of Logistic Regression and Random Forest.
* Understand the impact of imbalanced data and synthetic datasets on model performance.

---

## How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/fraud-detection-paysim.git
cd fraud-detection-paysim
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 4. Open the Project Notebook

Open:

```text
fraud_detection.ipynb
```

and run all cells sequentially.

---

## Tech Stack

### Programming Language

* Python

### Data Analysis

* Pandas
* NumPy

### Data Visualization

* Matplotlib
* Seaborn

### Machine Learning

* Scikit-learn

  * Logistic Regression
  * Random Forest Classifier
  * Train-Test Split
  * Classification Report
  * ROC Curve
  * ROC-AUC Score

### Development Environment

* Jupyter Notebook
* Google Colab

### Dataset

* PaySim Synthetic Financial Dataset

---

## Key Findings

* Fraud transactions represent a very small portion of the dataset, resulting in a highly imbalanced classification problem.
* Fraud activities primarily occur in TRANSFER and CASH_OUT transaction types.
* Logistic Regression achieved high recall but generated a large number of false positives.
* Random Forest achieved near-perfect performance due to highly separable fraud patterns within the synthetic dataset.
* Balance-related features were among the most important factors in identifying fraudulent transactions.

---

## Dataset Limitation

The PaySim dataset is synthetic and may not fully represent real-world banking fraud scenarios. As a result, fraud patterns can be more easily separated by machine learning models, leading to unusually high performance compared to real-world applications.
