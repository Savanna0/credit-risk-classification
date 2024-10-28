# credit-risk-classification

## Overview of the Analysis
In this module, we used the data from the csv file lending_data to train a machine learning model to help us evaluate loan risk. This model uses the data from a lending service company to help us identify the creditworthiness of borrowers. The model broke down the data to predict two categories of loans, healthy loans (0) and high-risk loan (1). 

When creating the model, the first stage of the machine learning process began with using the lending_data and separating the loan_status column from the data frame and creating the label (y). The remaining columns were used to create the features (X) from the data frame. 

Next, we split the data into training and testing sets. By importing sklearn.model_selection we split the data into X_train, X_test, y_train, y_test values.

Next, we used Logistic Regression Model to fit the model. Then by using this model, we use predictions on the testing data labels by using the testing feature data (X_test) and the fitted model.

Finally, we generated a confusion matrix for the model and printed a classification report for the model. This report shows us the precision and accuracy of the model. 

## Results
Machine Learning Model:

Accuracy = 99%

For Healthy loans (0) and high-risk loans (1)
-	Healthy loans (0)
o	Precision = 100%
o	Recall = 99%

-	High-risk loans (1)
o	Precision = 84%
o	Recall = 94%

## Summary
When looking at the results of the model, we see the model has a 99% accuracy for both the 0 (healthy loan) and 1 (high-risk loan) labels. However, if we look at the 0 and 1 labels individually, especially on the precision line, we see they are very different. For Healthy loans (0) we see a 100% precision rate and a 99% recall rate. While for the High-risk loan (1), we see 84% precision rate and a 94% recall rate. This difference shows us that it would be better to predict the Healthy loans (0) because of the higher precision rate. Even with this difference, we can expect the model to work relatively well, according to the accuracy rate of 99%. 

## Resources
Resources provided by instructor assistance, class material, instructor video recordings, and examples given from TTC Bootcamp. Xpert Learning Assistant provided by TCC Bootcamp. Tutoring provided by TTC Bootcamp.
