# COVID-19 Survey Data Analysis and Modelling

This repository contains a Jupyter Notebook (`Covid19-EDA.ipynb`) that performs exploratory data analysis (EDA) and builds machine learning models on the COVID-19 survey student responses dataset.

## Overview

The analysis covers various aspects of the dataset, including:

- Visualization of survey responses related to online classes, social media usage, lifestyle changes, and more.
- Preprocessing steps to handle missing values and convert categorical features into numerical format.
- Building and evaluating machine learning models for predicting the impact of the COVID-19 lockdown on students' health.

## Dataset

The dataset used in this analysis is the "COVID-19 Survey Student Responses" dataset. The original dataset source is mentioned in the code reference.

## Dependencies

Make sure to install the required dependencies by running:

```bash
git clone https://github.com/chiranjeevim27/EDA-Covid-19.git
```

```bash
pip install -r requirements.txt
```

## Usage

1. Open the Jupyter Notebook `buildwithai-eda-modelling.ipynb` using any compatible environment.
2. Execute the notebook cells sequentially to perform EDA and model training.

## Machine Learning Models Explored

1. **Logistic Regression**
   - Hyperparameter tuning using GridSearchCV.
   - Evaluation metrics: F1 score, confusion matrix.

2. **Support Vector Classifier (SVC)**
   - Hyperparameter tuning using GridSearchCV.
   - Visualization of hyperparameter impact using heatmaps.
   - Evaluation metrics: F1 score, confusion matrix.

3. **Random Forest Classifier**
   - Hyperparameter tuning using GridSearchCV.
   - Evaluation metrics: F1 score, confusion matrix.

4. **XGBoost Classifier**
   - Hyperparameter tuning using GridSearchCV.
   - Visualization of hyperparameter impact using heatmaps.
   - Evaluation metrics: F1 score, confusion matrix.

## Contributors

- Chiranjeevi M (https://github.com/chiranjeevim27/)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Feel free to explore, contribute, or provide feedback!
