# Credit Risk Prediction

## Table of Contents

1. [Overview](#overview)
2. [Features](#features)
3. [Project Structure](#project-structure)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Project Workflow](#project-workflow)
7. [Results](#results)
8. [Key Learnings](#key-learnings)
9. [Notes](#notes)
10. [Contributing](#contributing)
11. [License](#license)

---

## Overview

This project focuses on predicting the credit risk of loan applicants using machine learning models. The goal is to classify applicants into risk categories to support better lending decisions.

The workflow includes:

* Data preprocessing
* Exploratory Data Analysis (EDA)
* Feature engineering
* Model training and evaluation
* Hyperparameter tuning

---

## Features

* Data Exploration: Analyze distributions, correlations, and trends
* Feature Engineering: Create meaningful derived features
* Model Training: Train multiple machine learning and ensemble models
* Evaluation: Use metrics like accuracy, precision, recall, and specificity
* Hyperparameter Tuning: Improve performance using Bayesian Optimization

---

## Project Structure

```bash
├── credit-risk-prediction-training-and-eda.ipynb
├── README.md
├── requirements.txt
└── (optional) data/ , models/
```

---

## Installation

```bash
git clone https://github.com/abhnvgrg/credit-risk-prediction.git
cd credit-risk-prediction
pip install -r requirements.txt
```

---

## Usage

```bash
jupyter notebook credit-risk-prediction-training-and-eda.ipynb
```

Follow the notebook step-by-step to preprocess data, perform EDA, engineer features, train models, and evaluate results.

---

## Project Workflow

### 1. Data Preprocessing

* Handle missing values
* Encode categorical variables
* Scale numerical features

### 2. Exploratory Data Analysis (EDA)

* Visualize distributions and correlations
* Identify important features

### 3. Feature Engineering

* Created features such as:

  * `loan_to_income_ratio`
  * `loan_to_emp_length_ratio`
  * `int_rate_to_loan_amt_ratio`
* Grouped variables into categories such as age, income, and loan amount

### 4. Model Training

Models used:

* Logistic Regression
* Random Forest
* Gradient Boosting
* XGBoost
* LightGBM
* CatBoost

### 5. Hyperparameter Tuning

* Bayesian Optimization for performance improvement

### 6. Evaluation Metrics

* Accuracy
* Precision
* Recall
* Specificity

---

## Results

The final ensemble model achieved:

* Accuracy: 94.4%
* High precision resulting in fewer false positives
* High recall for better detection of risky applicants
* High specificity for reliable borrower classification

---

## Key Learnings

* Building end-to-end machine learning pipelines
* Feature engineering for financial datasets
* Model comparison and tuning
* Using ensemble learning to improve performance

---

## Notes

* Large datasets or models are not included in the repository
* Use Git LFS or external storage if required

---

## Contributing

Contributions are welcome. Feel free to fork the repository and submit pull requests.

---

## License

This project is licensed under the MIT License.
