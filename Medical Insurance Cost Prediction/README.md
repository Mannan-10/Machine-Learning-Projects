# Medical Insurance Cost Prediction

This project demonstrates the use of Linear Regression in Machine Learning to predict medical insurance costs based on various factors such as age, BMI, smoking habits, and more.

## Dataset Information

The dataset used for this project contains the following features:
- `age`: Age of the individual.
- `sex`: Gender of the individual.
- `bmi`: Body Mass Index, a measure of body fat based on height and weight.
- `children`: Number of children/dependents covered by health insurance.
- `smoker`: Smoking status of the individual (`yes` or `no`).
- `region`: Residential region in the US (northeast, southeast, southwest, northwest).
- `charges`: Medical insurance cost (target variable).

### Dataset Source
The dataset is publicly available on Kaggle: [Medical Cost Personal Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)

## Project Overview

The goal of this project is to:
1. Analyze the dataset to understand the relationships between features.
2. Build a Linear Regression model to predict insurance costs.
3. Evaluate the model's performance using metrics such as Mean Squared Error (MSE) and R-squared.

## Requirements

To run this project, you need the following Python libraries:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

## How to Run

1. Clone this repository:
    ```bash
    git clone https://github.com/Mannan_10/Machine-Learning-Projects/Medical-Insurance-Cost-Prediction.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Medical-Insurance-Cost-Prediction
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Run the Jupyter Notebook or Python script to train and evaluate the model.

## Results

The Linear Regression model provides insights into how different factors influence medical insurance costs. The results and visualizations are included in the project files.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
