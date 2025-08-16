# Sales Prediction

This project demonstrates a machine learning workflow for predicting sales based on advertising data. The notebook covers data exploration, visualization, preprocessing, model training, and evaluation.

## Dataset
- The dataset is loaded from `advertising.csv`.
- Features include TV, Radio, and Newspaper advertising budgets, with Sales as the target variable.

## Workflow
1. **Data Loading & Exploration**
    - Load the dataset and inspect its structure.
    - Visualize feature relationships with line plots and a correlation heatmap.
2. **Data Cleaning & Preprocessing**
    - Handle missing values and drop irrelevant features (e.g., Newspaper).
    - Split the data into features and target.
3. **Model Training**
    - Split the data into training and test sets.
    - Train a Linear Regression model to predict sales.
    - (RandomForestClassifier is imported but not used for regression.)
4. **Evaluation**
    - Evaluate the model using R2 score and Mean Absolute Percentage Error (MAPE).
    - Visualize actual vs. predicted sales for both training and test sets using matplotlib.

## Requirements
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Install dependencies with:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Usage
1. Place `advertising.csv` in the project directory.
2. Run the notebook `Sales Prediction.ipynb` step by step.
3. Review the visualizations and model performance metrics.

## Output
- Feature analysis and correlation plots.
- Model performance metrics (R2, MAPE).
- Scatter plots comparing actual vs. predicted sales for both training and test sets.

## Author
- Stuti Jain

---
This project provides a simple regression pipeline for sales prediction using advertising data.
