# Absenteeism Prediction Model

## Overview
This project aims to predict excessive absenteeism among employees using historical absence data. The model identifies patterns in the data to forecast whether an employee is likely to be excessively absent.

## Objectives
- **Predict** whether employees will be excessively absent.
- **Analyze** absence patterns to assist management in planning and decision-making.

## Methodology
1. **Data Preprocessing**:
   - Handled missing values and cleaned the dataset.
   - Created **dummy variables** for categorical features.
   - Generated **targets** for prediction using absence hours as a reference (inferred target due to absence of actual values).
2. **Feature Engineering**:
   - Standardized the data to ensure compatibility with the model.
3. **Modeling**:
   - Implemented a **Logistic Regression model** to predict excessive absenteeism.
4. **Evaluation**:
   - Tested the model’s performance using accuracy and other metrics to assess its reliability.

## Technologies Used
- **Python**: Pandas, Scikit-learn, NumPy
- **Logistic Regression**
- **Data Standardization** and Preprocessing

## Outcomes
- A **working model** capable of identifying employees likely to be excessively absent.
- Useful insights into absence patterns, enabling management to take proactive measures.
