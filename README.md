# Predicting Titanic Survival Using Machine Learning

## Executive Summary
This project applies machine learning techniques to predict passenger survival on the Titanic. The dataset includes details such as passenger demographics, ticket class, and fares. The study compares the effectiveness of Naïve Bayes and Logistic Regression in classifying survival outcomes.

## Business Problem
Predicting survival rates in historical disasters provides insights into key survival factors. The project addresses:
- How different factors (age, gender, class) influenced survival outcomes.
- Which classification model is most effective for predicting survival rates.
- The importance of feature selection and preprocessing in machine learning models.

## Methodology
- **Data Cleaning & Preparation**:
  - Removed null values and standardized categorical variables.
  - Created new features for better model performance.

- **Machine Learning Model Implementation**:
  - **Naïve Bayes Model**: Applied for probabilistic classification.
  - **Logistic Regression Model**: Used for binary classification.
  - Split data into training (70%) and testing (30%) sets.

## Model Evaluation:
- Assessed model performance using precision, recall, and accuracy metrics.
- Analyzed confusion matrices to identify model weaknesses.

## Technologies & Tools Used
- **Python (Pandas, NumPy, Scikit-learn)**: For data processing and model training.
- **Machine Learning Models**: Naïve Bayes & Logistic Regression.
- **Jupyter Notebook**: For experimentation and documentation.

## Key Findings
- Logistic Regression outperformed Naïve Bayes, achieving 65.38% accuracy.
- Naïve Bayes struggled with certain passenger classes, leading to lower precision.
- Feature engineering could improve prediction accuracy, especially in underrepresented classes.

## Business Recommendations
- **Feature Engineering**: Enhance dataset with additional survival-relevant attributes.
- **Model Optimization**: Explore ensemble learning methods (e.g., Random Forest, XGBoost) for improved accuracy.
- **Generalization Testing**: Apply the model to similar datasets (e.g., other maritime disasters) to evaluate robustness.

## Next Steps
- Optimize hyperparameters and test additional classification models.
- Implement data augmentation techniques to balance underrepresented classes.
- Develop an interactive web application for survival prediction.
