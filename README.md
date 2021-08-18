# Binary-Classifiaction---Rain-Prediction-in-Australia
EDA + Vizualization + Preprocessing + Feature Engineering + Modelling + Evaluation 

Results and Conclusion : -

1. The logistic regression model accuracy score is 0.8446. So, the model does a very good job in predicting whether or not it will rain tomorrow in Australia.

2. Small number of observations predict that there will be rain tomorrow. Majority of observations predict that there will be no rain tomorrow.

3. The model shows no signs of overfitting.

4. If we use more regularized model by setting C=0.01, then both the training and test set accuracy decrease relative to the default parameters.

5. Increasing the threshold level results in increased accuracy.

6. ROC AUC of our model approaches towards 1. So, we can conclude that our classifier does a good job in predicting whether it will rain tomorrow or not.

7. Our, original model score is found to be 0.8476. The average cross-validation score is 0.8474. So, we can conclude that cross-validation does not result in performance improvement.

8. Our original model test accuracy is 0.8442 while GridSearch CV accuracy is 0.8446. We can see that GridSearch CV slightly improve the performance for this particular model.
