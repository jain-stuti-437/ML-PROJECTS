# ML-PROJECTS
# House Price Prediction

This project is a machine learning pipeline for predicting house prices using various regression models. The workflow includes data preprocessing, feature engineering, model training, evaluation, and visualization.

## Dataset
- The dataset is loaded from `HousePricePrediction.xlsx`.
- It contains both numerical and categorical features relevant to house prices.

## Workflow
1. **Data Loading & Exploration**
    - Load the dataset and inspect its structure.
    - Visualize numerical and categorical features using scatter and bar plots.
    - Analyze feature correlations with a heatmap.
2. **Data Cleaning & Preprocessing**
    - Handle missing values by filling or dropping as appropriate.
    - Drop irrelevant columns (e.g., `Id`).
    - Encode categorical variables using OneHotEncoder.
    - Scale features using StandardScaler.
3. **Model Training**
    - Split the data into training and test sets.
    - Train three regression models:
        - Linear Regression
        - Random Forest Regressor
        - Support Vector Regressor (SVR)
4. **Evaluation**
    - Evaluate models using R2 score and Mean Absolute Percentage Error (MAPE).
    - Visualize actual vs. predicted prices for each model using matplotlib.

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
1. Place `HousePricePrediction.xlsx` in the project directory.
2. Run the notebook `House Price Prediction.ipynb` step by step.
3. Review the visualizations and model performance metrics to compare results.

## Output
- Plots for feature analysis and correlation.
- Model performance metrics (R2, MAPE).
- Scatter plots comparing actual vs. predicted prices for each model.

## Author
- Stuti jain

---
This project demonstrates a complete regression workflow for house price prediction using Python and popular machine learning libraries.

