
Step 01:

#Apply Linear Regression. Evaluate the ML Model.

#KNN Regressor:
1. Import data set
2. Seperate x and y (y=Weight)
3. Train = 70%, Test = 30%
4. ApplyLinear Regression
5. Evaluate Model (Accuracy, MSE, Prediction)
6. Apply KNN Regressor: https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsRegressor.html
7. Evaluate Model (Accuracy, MSE, Prediction)

Tuning:KNN Regressor
1. Apply Randomized Search CV to select best K vlaue (range 5-100, 50, weights=[])
2. Compare accuracy with default KNN and After tuning K value
3. Evaluate Model (Accuracy, MSE, Prediction) and Compare with Old KNN model and Linear regression as well.


Step 02:

KNN Classifier:
1. Import data set
2. Seperate x and y (y=Gender)
3. Train = 70%, Test = 30%
4. Apply KNN Classifier 
5. Evaluate Model (Accuracy, Confusion Matrix, ROC, AUC, Classification Report)
6. Apply KNN Classifier: https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html

Tuning:KNN Classifier 
1. Apply Randomized Search CV to select best K vlaue
2. Compare accuracy with default KNN and After tuning K value
3. Evaluate Model (Accuracy, Confusion Matrix, ROC, AUC, Classification Report) and Compare with Old KNN model

