# Rock vs Mine Prediction

This project demonstrates the use of Logistic Regression, a supervised machine learning algorithm, to classify objects as either rocks or mines based on their features.

## Dataset Information

The dataset used for this project is the **Sonar Dataset**, which contains 208 samples with 60 features each. Each sample represents the energy of sonar signals bounced off an object, and the goal is to classify the object as either a rock (`R`) or a mine (`M`).

- **Features**: 60 numerical attributes representing sonar signal frequencies.
- **Target**: Binary classification (`R` for Rock, `M` for Mine).

### Source

The dataset can be downloaded from the UCI Machine Learning Repository:  
[Sonar Dataset - UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/connectionist+bench+(sonar,+mines+vs.+rocks))

## Project Workflow

1. **Data Preprocessing**:
    - Load the dataset.
    - Handle missing values (if any).
    - Normalize the feature values for better performance.

2. **Model Training**:
    - Split the dataset into training and testing sets.
    - Train a Logistic Regression model on the training data.

3. **Model Evaluation**:
    - Evaluate the model's performance using metrics such as accuracy, precision, recall, and F1-score.

4. **Prediction**:
    - Use the trained model to predict whether a given object is a rock or a mine.

## Requirements

- Python 3.x
- Libraries: `numpy`, `pandas`, `scikit-learn`, `matplotlib`

## How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/Mannan-10/Machine-Learning-Projects.git
    ```
    ```
    cd "Rock vs Mine Prediction"
    ```

2. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the script:
    ```bash
    python rock_vs_mine_prediction.py
    ```

## Results

The Logistic Regression model achieves a reasonable accuracy in classifying rocks and mines. Further improvements can be made by experimenting with feature engineering and hyperparameter tuning.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
