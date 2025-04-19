# Credit Card Fraud Detection using Logistic Regression

This project demonstrates the use of Logistic Regression, a supervised machine learning algorithm, to detect fraudulent credit card transactions. The goal is to classify transactions as fraudulent or legitimate based on the provided dataset.

## Dataset

The dataset used for this project is the [Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud), which contains transactions made by European cardholders in September 2013. It includes 284,807 transactions, out of which 492 are fraudulent. The dataset is highly imbalanced, with the positive class (frauds) accounting for only 0.172% of all transactions.

### Features

- The dataset contains 31 columns:
    - **V1, V2, ..., V28**: Principal components obtained using PCA (to protect sensitive information).
    - **Time**: Seconds elapsed between the first transaction and each subsequent transaction.
    - **Amount**: Transaction amount.
    - **Class**: Target variable (0 for legitimate, 1 for fraudulent).

### Download Source

You can download the dataset from [Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud).

## Project Workflow

1. **Data Preprocessing**:
     - Handle missing values (if any).
     - Normalize the `Amount` and `Time` columns.
     - Split the dataset into training and testing sets.

2. **Exploratory Data Analysis (EDA)**:
     - Analyze the class imbalance.
     - Visualize correlations and distributions.

3. **Model Training**:
     - Train a Logistic Regression model on the training data.
     - Use techniques like oversampling (SMOTE) or undersampling to address class imbalance.

4. **Model Evaluation**:
     - Evaluate the model using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.

5. **Deployment**:
     - Save the trained model for future predictions.

## Requirements

- Python 3.x
- Libraries: `numpy`, `pandas`, `scikit-learn`, `matplotlib`, `seaborn`

## How to Run

1. Clone the repository:
     ```bash
     git clone https://github.com/Mannan-10/Machine-Learning-Projects/Credit-Card-Fraud-Detection.git
     ```

     ```
     cd Credit-Card-Fraud-Detection
     ```

2. Install dependencies:
     ```bash
     pip install -r requirements.txt
     ```

3. Run the script:
     ```bash
     python fraud_detection.py
     ```

## Results

The Logistic Regression model achieves high precision and recall for the minority class (fraudulent transactions) after addressing the class imbalance. Detailed evaluation metrics and visualizations are provided in the project.

## Acknowledgments

- Dataset provided by [Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud).
- Special thanks to the ULB Machine Learning Group for making the dataset publicly available.
