# Loan-Prediction

Loan prediction is a critical task in the banking and financial industry, where the goal is to assess the creditworthiness of loan applicants and predict whether they are likely to repay the loan or default on their payments. The business understanding part of loan prediction involves gaining a clear understanding of the problem, its significance, and the specific objectives of the prediction model. The primary objective of loan prediction is to minimize the risk of default and financial losses for the lending institution. By accurately assessing the creditworthiness of loan applicants, the bank can make informed decisions about approving or rejecting loan applications. This process helps maintain a healthy loan portfolio, minimize defaults, and maximize profitability. To build an effective loan prediction model, it is essential to have access to historical loan data that includes information about borrowers, their financial attributes, loan terms, and whether they have repaid the loan or defaulted in the past. The availability and quality of data play a crucial role in the accuracy and reliability of the prediction model. The target variable in loan prediction is typically binary, indicating whether a borrower will default (1) or not (0) on their loan repayment. This variable is used to train the prediction model, making it capable of classifying new loan applications into default or non-default categories.
In this project I followed the CRISP-DM process.

## Summary of the basic tasks of my project:

1) Data exploration: I had two datasets, one called "train" and the other called "test." The "train" dataset contained the loan_status target column, while the "test" dataset did not. this phase contains data understading and visualization.

2) Data Preparation: I did the preparation tasks on both of the datasets.

3) Splitting the Data: I splited the "train" dataset into X_train and y_train, where X_train represents the features and y_train represents the loan_status target.

4) Algorithm Selection: I applied various algorithms, including logistic regression, K-nearest neighbors (KNN), decision tree, random forest, linear SVM, RBF SVM, naive Bayes, XGBoost, LightGBM, and CatBoost, for loan prediction.

5) Cross-Validation and Evaluation: I performed cross-validation using metrics such as mean accuracy and AUC-ROC to evaluate the performance of each algorithm. I also calculated additional metrics such as precision, recall, and F1 score.

6) Selection of Logistic Regression: Based on the evaluation results, I selected the logistic regression algorithm as the best performing model for loan prediction.

7) Prediction on Test Data: Using the trained logistic regression model, I made predictions on the test dataset, which did not have the loan_status column. These predictions provided the estimated loan_status values for the test data.

8) Analysis and Interpretation: I compared the distribution of predicted loan_status values in the test dataset to the distribution of loan_status values in the training dataset. This allowed me to observe how the predictions aligned with the overall loan_status distribution.
