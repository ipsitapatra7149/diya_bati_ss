# PREDICTION OF AGE OF ONSET OF DIABETES FOR AN INDIAN NON-DIABETIC PERSON USING ML REGRESSION 

This machine learning project aims to predict the age of onset of diabetes for Indian non-diabetic individuals based on a range of genetic, lifestyle, and medical features. The goal is to use regression techniques to estimate when a person might develop diabetes, helping in early preventive healthcare interventions.

Problem Statement:
Diabetes is a rapidly growing public health concern in India, with an increasing number of individuals being diagnosed at a younger age. Most machine learning models and healthcare solutions available today focus on detecting diabetes after its onset. However, very few models are designed to predict when a person is likely to develop the condition—especially in individuals who are currently non-diabetic.
This project addresses that gap by building a machine learning regression model that predicts the age of onset of diabetes for Indian non-diabetic individuals. The model uses a combination of genetic, lifestyle, and medical history factors to provide a personalized prediction.

Real-World Scenario
Imagine a 25-year-old Indian individual with a strong family history of diabetes. Currently, they have no symptoms and test negative for diabetes. However, based on their genetics, lifestyle, and dietary habits, our model predicts that they are likely to develop diabetes at the age of 38.
This advance prediction gives them over a decade of preparation, during which they can:
1.Modify their diet and lifestyle
2.Increase physical activity
3.Monitor glucose levels regularly
4.Potentially delay or avoid the onset altogether
By offering such personalized foresight, this model empowers individuals to take preventive actions and allows healthcare professionals to intervene earlier. This can significantly reduce long-term complications and the burden on India's healthcare system.


Features Used
The dataset includes a variety of relevant features:

Family history of diabetes (yes/no)
Current age
Age at diagnosis (for relatives)
Duration of family member’s diabetes
HbA1c levels (if known)
Medication usage (e.g., preventive meds)
Dietary habits
Physical activity level
BMI and body weight history
Smoking/alcohol history (if applicable)

The dataset has been curated manually or collected via survey to suit the Indian demographic.

Tools & Technologies
Python 3.x
Pandas, NumPy – Data handling
Matplotlib, Seaborn – Visualization
Scikit-learn – ML modeling
XGBoost / Random Forest / Linear Regression – Regression models
Jupyter Notebook / Google Colab – Experimentation

Approach
Data Collection – Gathered data from surveys, research papers, and medical records.
Preprocessing – Cleaned and normalized the data. Handled missing values.
Feature Engineering – Encoded categorical data, generated new features.
Modeling – Tried multiple regression models (Linear, Random Forest, XGBoost).
Evaluation – Used MAE, RMSE, R² Score to compare model performance.
Prediction – Final model used to estimate the age of diabetes onset.


---------------------------------------------------------------------------------------------------------------
Shahid_DTR.ipynb : This file contains the work I previously did with my Decision Tree Regresstion Model
                   Uses the Train-Test split Method
                   Does not contain the modifications that were recently conveyed


trying_cross_validation.ipynb : This file contains the recent work I did on the same model, but by using Cross-Validation instead of Train-Test split Method

The reason being, the inclusion of only the training dataset.


Both the models are trained on the following dataset : Diabetic_expandeddataset.xlsx


**What is Validation in Machine Learning?**

Validation is the process of evaluating a model during training to tune hyperparameters, detect overfitting, and ensure generalization to unseen data. It acts as a "proxy" test set to guide model improvement before final evaluation on the test set.


**Key Purposes of Validation**
1. Hyperparameter Tuning

  Adjusting model settings (e.g., learning rate, network depth) based on validation performance.
  Example: Trying 10 different hyperparameter combinations and picking the one with the best validation accuracy.

2. Model Selection

  Choosing between different algorithms (e.g., random forest vs. SVM) or architectures.

3. Overfitting Detection

  If training accuracy keeps improving but validation accuracy plateaus/drops, the model is overfitting to the training     data.

4. Data Leakage Prevention

  The test set must remain untouched until the final evaluation. Validation ensures you don’t indirectly "peek" at the test   set during development


DATASET: 
  Diabetic_expandeddataset-maryada
  Diabetic_Synthetic_Merged_Fixed-ipsita
  Diabetic_Merged-combiantion of all
