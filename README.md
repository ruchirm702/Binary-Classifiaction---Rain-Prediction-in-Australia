# Binary Classification - Rain Prediction in Australia

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
