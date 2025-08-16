# Titanic Survival Prediction

This project demonstrates a complete machine learning workflow for predicting passenger survival on the Titanic using multiple classification models. The notebook covers data cleaning, feature engineering, model training, evaluation, and visualization.

## Dataset
- The dataset is loaded from `Titanic-Dataset.csv`.
- Features include passenger demographics, ticket information, and fare details.

## Workflow
1. **Data Loading & Exploration**
    - Load the dataset and inspect its structure.
    - Handle missing values using imputation for both numerical and categorical features.
    - Drop irrelevant columns (e.g., PassengerId, Name, Ticket, Cabin).
2. **Feature Engineering**
    - Encode categorical variables using OneHotEncoder.
    - Scale features using StandardScaler.
3. **Model Training**
    - Split the data into training and test sets.
    - Train and evaluate multiple classifiers:
        - Random Forest Classifier
        - Support Vector Machine (SVM)
        - Logistic Regression
4. **Evaluation & Visualization**
    - Evaluate models using accuracy, confusion matrix, and classification report.
    - Visualize predictions with scatter plots (Age vs Fare, colored by predicted survival for each model).

## Requirements
- Python 3.x
- pandas
- numpy
- matplotlib
- scikit-learn

Install dependencies with:
```bash
pip install pandas numpy matplotlib scikit-learn
```

## Usage
1. Place `Titanic-Dataset.csv` in the project directory.
2. Run the notebook `Titanic survival.ipynb` step by step.
3. Review the visualizations and model performance metrics.

## Output
- Model performance metrics (accuracy, confusion matrix, classification report).
- Scatter plots comparing Age vs Fare colored by predicted survival for each model.

## Author
- Stuti Jain

---
This project provides a practical example of classification and data preprocessing for the Titanic dataset using Python and scikit-learn.
