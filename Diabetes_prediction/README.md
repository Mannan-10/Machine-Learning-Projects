# Diabetes Prediction Using SVM

This project demonstrates the use of Support Vector Machines (SVM) for predicting diabetes based on medical diagnostic data. The goal is to classify whether a patient has diabetes or not using features such as glucose level, blood pressure, and more.

## Dataset

The dataset used for this project is the **Pima Indians Diabetes Database**, which is publicly available on the [Kaggle website](https://www.kaggle.com/uciml/pima-indians-diabetes-database). It contains the following features:

- **Pregnancies**: Number of times pregnant
- **Glucose**: Plasma glucose concentration
- **BloodPressure**: Diastolic blood pressure (mm Hg)
- **SkinThickness**: Triceps skinfold thickness (mm)
- **Insulin**: 2-Hour serum insulin (mu U/ml)
- **BMI**: Body mass index (weight in kg/(height in m)^2)
- **DiabetesPedigreeFunction**: Diabetes pedigree function
- **Age**: Age (years)
- **Outcome**: Class variable (0 if non-diabetic, 1 if diabetic)

## Prerequisites

To run this project, you need the following installed:

- Python 3.x
- Libraries: `numpy`, `pandas`, `scikit-learn`, `matplotlib`

Install the required libraries using:
```bash
pip install numpy pandas scikit-learn matplotlib
```

## Project Structure

- `diabetes.csv`: The dataset file.
- `diabetes_prediction.py`: Python script for training and testing the SVM model.
- `README.md`: Project documentation.

## Steps to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/Mannan-10/Machine-Learning-Projects/Diabetes_prediction.git
    ```

    ```bash
    cd Diabetes_prediction
    ```

2. Place the dataset (`diabetes.csv`) in the project directory.

3. Run the script:
    ```bash
    python diabetes_prediction.py
    ```

4. The script will output the model's accuracy and predictions.

## Results

The SVM model achieves a high accuracy in predicting diabetes. The results may vary depending on the hyperparameters and data preprocessing steps.

## Future Improvements

- Experiment with different kernels (e.g., RBF, polynomial) for SVM.
- Perform feature engineering to improve model performance.
- Use cross-validation for better evaluation.

## References

- [Pima Indians Diabetes Database on Kaggle](https://www.kaggle.com/uciml/pima-indians-diabetes-database)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/)
