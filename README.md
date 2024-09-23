# Binary Classification - Rain Prediction in Australia

![Python](https://img.shields.io/badge/Python-306998?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Numpy](https://img.shields.io/badge/Numpy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3776AB?style=for-the-badge&logo=matplotlib&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-1f77b4?style=for-the-badge&logo=seaborn&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-FF6F00?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Logistic Regression](https://img.shields.io/badge/Logistic%20Regression-019875?style=for-the-badge&logo=regression&logoColor=white)
![GridSearchCV](https://img.shields.io/badge/GridSearchCV-FF5733?style=for-the-badge&logo=search&logoColor=white)
![Cross Validation](https://img.shields.io/badge/Cross%20Validation-6A5ACD?style=for-the-badge&logo=cv&logoColor=white)
![ROC AUC](https://img.shields.io/badge/ROC%20AUC-32CD32?style=for-the-badge&logo=roc&logoColor=white)

## EDA + Visualization + Preprocessing + Feature Engineering + Modelling + Evaluation
## Results and Conclusion

1. **Logistic Regression Model Performance**
   - **Accuracy Score**: 0.8446
   - The model performs very well in predicting whether or not it will rain tomorrow in Australia.

2. **Prediction Distribution**
   - A small number of observations predict that there will be rain tomorrow.
   - The majority of observations predict that there will be no rain tomorrow.

3. **Model Overfitting**
   - The model shows no signs of overfitting, indicating good generalization to unseen data.

4. **Regularization Impact**
   - Using a more regularized model (C=0.01) results in decreased accuracy for both the training and test sets compared to the default parameters.

5. **Threshold Adjustment**
   - Increasing the threshold level results in increased accuracy, showcasing the importance of threshold tuning.

6. **ROC AUC**
   - The ROC AUC of the model approaches 1, indicating that the classifier does a good job in predicting whether it will rain tomorrow or not.

7. **Cross-Validation**
   - Original Model Score: 0.8476
   - Average Cross-Validation Score: 0.8474
   - Cross-validation does not significantly improve performance, as evidenced by the minimal difference between the original model score and the average cross-validation score.

8. **GridSearch CV Performance**
   - Original Model Test Accuracy: 0.8442
   - GridSearch CV Accuracy: 0.8446
   - GridSearch CV slightly improves the performance of this particular model.

### Summary
- The logistic regression model is effective in predicting rain in Australia with an accuracy of 0.8446.
- The model maintains good generalization without overfitting.
- Adjustments in regularization and threshold can influence model performance.
- The ROC AUC score confirms the classifier's reliability.
- Cross-validation and GridSearch CV provide insights into model stability and slight performance enhancements.

---
This report presents a clear and concise overview of the logistic regression model's performance in predicting rain in Australia, highlighting the key findings and implications of the results.
