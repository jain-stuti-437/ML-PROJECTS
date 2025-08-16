# IRIS Flower Classification

This project demonstrates a machine learning workflow for classifying iris flower species using the classic IRIS dataset. The notebook covers data exploration, preprocessing, model training, evaluation, and visualization.

## Dataset
- The dataset is loaded from `IRIS.csv`.
- Features include sepal length, sepal width, petal length, and petal width.
- The target is the species of the iris flower.

## Workflow
1. **Data Loading & Exploration**
    - Load the dataset and inspect its structure.
    - Check for missing values and basic statistics.
2. **Data Preprocessing**
    - Split the data into features and target.
    - Standardize features using StandardScaler.
3. **Model Training**
    - Split the data into training and test sets.
    - Train a Random Forest Classifier to predict the species.
4. **Evaluation & Visualization**
    - Evaluate the model using confusion matrix, accuracy, and classification report.
    - Visualize the confusion matrix using matplotlib.

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
1. Place `IRIS.csv` in the project directory.
2. Run the notebook `IRIS FLOWER CLASSIFICATION.ipynb` step by step.
3. Review the visualizations and model performance metrics.

## Output
- Model performance metrics (accuracy, confusion matrix, classification report).
- Confusion matrix heatmap for model predictions.

## Author
- Stuti Jain

---
This project provides a practical example of classification and data preprocessing for the IRIS dataset using Python and scikit-learn.
