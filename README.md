Data was provide on loans in order to build a model that would be able to accurately predict healthy and high-risk loans. I used the original data to create a logistic regression model. The findings were as follows:
•	The accuracy score for the model was 95.2%.
•	Of the healthy loans, 102 ended up being high-risk loans.
•	10% of the high-risk loans were misclassified and were actually healthy loans.
The count of the two types of loans were quite imbalanced. I decided to run another logistic regression model with resampled data in hopes of being able to more accurately predict the loan types. The findings for the second model were as follows:
•	The accuracy score for this model was 99.4%.
•	Of the healthy loans, 116 ended up being high risk loans.
•	The model did better with the high-risk loans. Only 4 of the high-risk loans were actually healthy loans. The model identified approximately 100 additional high-risk loans that the first model missed.
The resampled data model performed significantly better than the original model. It would be my recommendation to use this model and retrain it with new loan data to try to raise the efficiency even more.
