# Titanic Survival Prediction

This project uses the Titanic dataset to build a model that predicts whether a passenger on the Titanic survived or not. This is a classic beginner project that involves data cleaning, feature engineering, and machine learning model building.

## Dataset

The dataset used in this project can be downloaded from [Kaggle](https://www.kaggle.com/datasets/yasserh/titanic-dataset). It contains information about individual passengers such as age, gender, ticket class, fare, cabin, and survival status.

## Installation

1. Clone the repository:
    ```sh
    git clone https:/github.com/Saravana999/titanic-survival-prediction.git
    cd titanic-survival-prediction
    ```

2. Install the required libraries:
    ```sh
    pip install pandas numpy seaborn matplotlib scikit-learn
    ```

## Usage

1. Download the dataset from Kaggle and place the CSV file in the project directory.
2. Update the `file_path` variable in the code to point to the location of your Titanic dataset CSV file.
3. Run the Python script:
    ```sh
    python titanic_survival_prediction.py
    ```

## Project Structure

- `titanic_survival_prediction.py`: Main script for data preprocessing, model building, and evaluation.
- `README.md`: This file.

## Code Explanation

1. **Data Loading**: The dataset is loaded using `pandas`.
2. **Data Exploration**: Basic information and statistics about the dataset are displayed.
3. **Data Cleaning**: Missing values are handled, and unnecessary columns are dropped.
4. **Feature Engineering**: Categorical variables are converted to numerical, and relevant features are selected.
5. **Model Building**: A RandomForestClassifier is used to train the model.
6. **Model Evaluation**: The model's performance is evaluated using accuracy, confusion matrix, and classification report. Feature importance is also visualized.

## Results

- Accuracy: [0.8202247191011236]
- Confusion Matrix: [90 15]
                    [17 57]

- Classification Report:precision    recall  f1-score   support
                   
                  0       0.84      0.86      0.85       105
                  1       0.79      0.77      0.78        74
           
           accuracy                           0.82       179

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

