# Predict the Success of Bank Telemarketing

This project is a solution for the [Predict the Success of Bank Telemarketing](https://www.kaggle.com/competitions/predict-the-success-of-bank-telemarketing/overview) Kaggle competition. The goal is to predict whether a client will subscribe to a term deposit based on their personal and campaign-related information.

## Problem Statement

Banks use telemarketing campaigns to offer term deposits to clients. The challenge is to predict the success of these campaigns (i.e., whether a client will subscribe) using historical data.

## Dataset

The dataset contains information about clients, their last contact with the bank, and the outcome of previous campaigns.  
- **train.csv**: Training data with features and target variable (`target`: yes/no).
- **test.csv**: Test data for which predictions are to be made.
- **sample_submission.csv**: Format for submission.

For detailed feature descriptions, see the [Kaggle Data page](https://www.kaggle.com/competitions/predict-the-success-of-bank-telemarketing/data).

## Project Structure

```
23ds1000028-notebook-t32024.ipynb   # Main notebook with data analysis, preprocessing, modeling, and prediction
README.md                           # Project documentation (this file)
sample_submission.csv               # Sample submission format
test.csv                            # Test dataset
train.csv                           # Training dataset
```

## Approach

- **Data Cleaning & Preprocessing**: Handling missing values, feature engineering (e.g., extracting date features), and encoding categorical variables.
- **Modeling**: Multiple machine learning models are explored, including ensemble methods (CatBoost, XGBoost, LightGBM, Random Forest, etc.).
- **Evaluation**: Models are evaluated using accuracy, F1-score, and other relevant metrics.
- **Submission**: Predictions are generated for the test set and saved in the required format.

## How to Run

1. Clone this repository.
2. Open `23ds1000028-notebook-t32024.ipynb` in Jupyter or VS Code.
3. Run the notebook cells in order to preprocess data, train models, and generate predictions.
4. The final predictions will be saved as `submission.csv`.


## References

- [Competition Overview](https://www.kaggle.com/competitions/predict-the-success-of-bank-telemarketing/overview)
- [Competition Data](https://www.kaggle.com/competitions/predict-the-success-of-bank-telemarketing/data)

---

*This project is for educational purposes and as a submission to the Kaggle competition.*