# Heart Disease Prediction

This project focuses on predicting the likelihood of heart disease using Logistic Regression, a popular machine learning algorithm for binary classification tasks.

## Overview

Heart disease is one of the leading causes of death worldwide. Early prediction of heart disease can help in taking preventive measures and improving patient outcomes. This project uses a dataset containing various health metrics to train a Logistic Regression model to predict whether a person is at risk of heart disease.

## Dataset

The dataset used for this project can be downloaded from the [UCI Machine Learning Repository](https://drive.google.com/file/d/1CEql-OEexf9p02M5vCC1RDLXibHYE9Xz/view).

## Features

The dataset includes the following features:
- Age
- Sex
- Chest pain type
- Resting blood pressure
- Serum cholesterol
- Fasting blood sugar
- Resting electrocardiographic results
- Maximum heart rate achieved
- Exercise-induced angina
- ST depression induced by exercise
- Slope of the peak exercise ST segment
- Number of major vessels colored by fluoroscopy
- Thalassemia

## Steps

1. **Data Preprocessing**: Handle missing values, encode categorical variables, and normalize numerical features.
2. **Exploratory Data Analysis (EDA)**: Analyze the relationships between features and the target variable.
3. **Model Training**: Train a Logistic Regression model using the processed dataset.
4. **Evaluation**: Evaluate the model's performance using metrics such as accuracy, precision, recall, and F1-score.
5. **Prediction**: Use the trained model to predict heart disease risk for new data.

## Requirements

- Python 3.x
- Libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Mannan-10/Machine-Learning-Projects/Heart-Disease-Prediction.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Heart-Disease-Prediction
    ```
3. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the Jupyter Notebook or Python script to train the model:
    ```bash
    python heart_disease_prediction.py
    ```
2. Use the trained model to make predictions on new data.

## Results

The Logistic Regression model achieved satisfactory performance on the test dataset, demonstrating its effectiveness in predicting heart disease risk.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The dataset is provided by the [UCI Machine Learning Repository](https://drive.google.com/file/d/1CEql-OEexf9p02M5vCC1RDLXibHYE9Xz/view).
- Special thanks to the open-source community for providing tools and resources.
