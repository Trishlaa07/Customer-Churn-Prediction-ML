# Customer Churn Prediction Using Machine Learning

## Project Overview
This project aims to predict customer churn for a telecom company using machine learning techniques.  
Predicting churn helps businesses identify customers likely to leave and take proactive retention actions.

## Dataset
The dataset used is the [Telco Customer Churn dataset from Kaggle](https://www.kaggle.com/blastchar/telco-customer-churn).  
It contains customer demographics, account information, and service usage data.

## Technologies Used
- Python  
- pandas  
- scikit-learn  
- seaborn  
- matplotlib  

## Methodology
1. Data preprocessing: Handle missing values, convert categorical variables to numeric using one-hot encoding.  
2. Model training: Used Random Forest Classifier for churn prediction.  
3. Hyperparameter tuning: Improved model performance with GridSearchCV.  
4. Model evaluation: Used accuracy, classification report, confusion matrix, and ROC curve.

## How to Run
1. Upload the dataset file (`WA_Fn-UseC_-Telco-Customer-Churn.csv`) to your working directory.  
2. Run the Jupyter notebook or Colab notebook `Customer-Churn-Prediction.ipynb`.  
3. Ensure the required Python libraries are installed (see `requirements.txt` if available).

## Results
- Initial model accuracy: ~[Insert your initial accuracy]%  
- Tuned model accuracy: ~[Insert your tuned accuracy]%  
- Visualization of confusion matrices and ROC curve included in the notebook.

## Future Work
- Deploy model as a web app using Flask or Streamlit.  
- Incorporate more features and deep learning models for better performance.  
- Use real-time data streams for dynamic churn prediction.

