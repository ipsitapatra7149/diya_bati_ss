# PREDICTION OF AGE OF ONSET OF DIABETES FOR AN INDIAN NON-DIABETIC PERSON USING ML REGRESSION 

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
