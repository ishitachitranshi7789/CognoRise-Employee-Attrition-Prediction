# Employee Attrition Prediction | CognoRise Infotech

## Project Overview
This project uses Machine Learning to predict employee attrition (whether an employee may leave an organization). It was completed as part of the CognoRise Infotech Machine Learning Internship.

## Objectives
- Explore employee data and identify patterns related to attrition.
- Clean and prepare data for Machine Learning.
- Train and compare classification models.
- Evaluate models using Accuracy, Precision, Recall, F1 Score, and ROC-AUC.
- Identify features associated with employee attrition.

## Dataset
IBM HR Analytics Employee Attrition & Performance dataset.

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Joblib
- Google Colab

## Workflow
1. Load and inspect the dataset.
2. Check missing values and duplicate records.
3. Explore attrition patterns using visualizations.
4. Encode categorical variables.
5. Split data into training and testing sets.
6. Train Logistic Regression, Decision Tree, and Random Forest classifiers.
7. Compare model performance using classification metrics.
8. Select and save the model with the highest ROC-AUC score.
9. Review feature importance.

## Model Evaluation
Models are compared using:
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

See the notebook for the actual evaluation results.

## Key Insights
The analysis explores how factors such as age, job satisfaction, and overtime relate to employee attrition. Refer to the notebook outputs for data-backed findings.

## Repository Files
- `Employee_Attrition_Prediction_CognoRise.ipynb` — analysis and model training notebook
- `employee_attrition_cleaned.csv` — cleaned dataset
- `employee_attrition_model.pkl` — saved best-performing model

## Conclusion
This project demonstrates an end-to-end employee attrition classification workflow, from exploratory data analysis to model evaluation and saving the selected model.

---
Created as part of the CognoRise Infotech Machine Learning Internship.
