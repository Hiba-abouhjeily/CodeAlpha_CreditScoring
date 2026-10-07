# CodeAlpha_CreditScoring

## Project Overview
This project is developed as part of the **CodeAlpha Machine Learning Internship** (Task 1: Credit Scoring Model). The objective is to predict an individual's creditworthiness using past financial and personal history data.

## Technologies Used
* **Python**
* **Pandas & NumPy** (Data manipulation and preprocessing)
* **Scikit-Learn** (Classification algorithms and evaluation metrics)
* **Jupyter Notebook**

## Dataset
* **File:** `german_credit_data.csv`
* **Features Include:** Age, Sex, Job, Housing, Saving accounts, Checking account, Credit amount, Duration, and Purpose.
* **Target Variable:** Binary classification column (`High_Credit`) created based on the credit amount median.

## Approach & Workflow
1. **Data Preprocessing:** Handled missing values (imputed missing savings/checking accounts with 'unknown') and dropped unnecessary columns.
2. **Feature Engineering:** Built a binary target variable from financial history attributes.
3. **Data Splitting:** Divided the dataset into training and testing sets using an 80-20 split.
4. **Scaling & Encoding:** Applied `StandardScaler` for numerical features and `OneHotEncoder` for categorical features.
5. **Model Training & Evaluation:** Trained and evaluated multiple classification algorithms (Random Forest, Logistic Regression, and K-Nearest Neighbors) assessing performance using metrics like Accuracy, Precision, Recall, F1-Score, and ROC-AUC

## How to Run
1. Clone this repository or download the files.
2. Ensure you have Python and the required libraries installed (`pandas`, `numpy`, `scikit-learn`).
3. Open `credit_scoring.ipynb` in Jupyter Notebook and run the cells sequentially.
