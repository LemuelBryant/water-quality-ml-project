# Water Potability Prediction Using Machine Learning

## Objective

Develop a baseline machine learning model to predict whether a water sample is potable based on its physicochemical properties while demonstrating an end-to-end data science workflow, including data acquisition, cleaning, exploratory data analysis, model development, and evaluation.

## Tools

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Flask (planned)
- Git and Github

## Project Progress

- [x] Github repository
- [x] Environment setup
- [x] Dataset acquisition
- [x] Initial data exploration
- [x] Data cleaning
- [x] Exploratory data analysis
- [x] Modeling
- [ ] Flask website

## Dataset

This project uses the Water Quality and Potability dataset from Kaggle. The dataset contains physicochemical measurements of water samples and a binary target variable indicating whether each sample is potable.

## Key Results

- Built a baseline Random Forest classifier
- Achieved 67% classification accuracy on the test set
- Median imputation was used to handle missing values
- Exploratory data analysis showed weak correlations between individual features and water potability
- Model performance suggests that predicting water potability requires combining multiple water quality measurements rather than relying on any single feature