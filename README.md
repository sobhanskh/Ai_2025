# Company_Data - Sales Prediction using Decision Tree

This project aims to analyze sales data from a company and identify which features most influence product sales using a **Decision Tree Classifier**.

## Dataset Overview

The dataset contains 400 entries and 11 features related to sales, marketing, and demographic data:

- **Sales**: Product sales (continuous value)
- **CompPrice**: Competitor product price
- **Income**: Average income of the local population
- **Advertising**: Advertising budget
- **Population**: Population size of the region
- **Price**: Product price
- **ShelveLoc**: Product's shelf location in the store (categorical: Bad, Medium, Good)
- **Age**: Average age of the customer base
- **Education**: Average education level of the region
- **Urban**: Whether the store is in an urban area (Yes/No)
- **US**: Whether the store is located in the United States (Yes/No)

## Objective

The main objective of this project is to:

- Convert the continuous `Sales` feature into categorical classes (e.g., High and Low sales).
- Build a **Decision Tree model** to predict the sales category.
- Analyze **feature importance** to identify the key drivers of high sales.

## Methods Used

- Data Cleaning and Preprocessing
- Feature Encoding (Label Encoding for categorical features)
- Decision Tree Classification (using scikit-learn)
- Model Evaluation (accuracy, confusion matrix, feature importance)
- Visualization of the Decision Tree and important features

## Tools & Libraries

- Python 3
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## Results

The model helps identify which features (e.g., Shelf Location, Price, Advertising) are most influential in predicting whether a product will have high or low sales.

## Future Work

- Try other classification models like Random Forest or Gradient Boosting.
- Perform hyperparameter tuning for better accuracy.
- Deploy the model as a simple web app for business use.
