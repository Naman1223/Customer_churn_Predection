# Telco Customer Churn Prediction

## Project Overview
This project aims to predict customer churn for a telecommunications company. By analyzing various customer attributes and service usage, we build a model to identify customers who are likely to churn.

## Data Source
The data used in this project is from the Telco Customer Churn dataset.

## Files in this Repository
- `WA_Fn-UseC_-Telco-Customer-Churn.csv`: The raw dataset containing customer information.
- `telco_churn_prediction.ipynb`: The Jupyter notebook containing the data cleaning, preprocessing, model building, and evaluation steps.

## Getting Started
1. Clone this repository: `git clone <repository_url>`
2. Install the required libraries: `pip install pandas numpy matplotlib scikit-learn tensorflow`
3. Open the notebook `telco_churn_prediction.ipynb` in Google Colab or a Jupyter environment.
4. Run the cells in the notebook to see the data analysis and model training process.

## Data Preprocessing
The notebook includes steps for:
- Handling missing values
- Encoding categorical features
- Scaling numerical features

## Model
A deep learning model built with TensorFlow/Keras is used for churn prediction.

## Results
The model's performance is evaluated using metrics such as accuracy, precision, recall, and F1-score.

## Future Improvements
- Explore other machine learning models.
- Perform hyperparameter tuning for the current model.
- Investigate feature engineering techniques.
- Analyze the impact of different features on churn.
