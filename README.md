# NovartisHiringChallenge 

This Repository consists of the predictive model that was designed to predict if a Server was Hacked or Not for the Novartis Hiring Challenge that was put out on HackerEarth. 

The dataset consisted of anonymized highly categorical variables and the class labels were severely imbalanced. After initial EDA, in the solution I came up featurizations such as Response Coding (which proved to be valuable) and OHE(not much value as features were hihgly categorical). After featurizations, we started from simple models such as KNN and Naive Bayes, then tried linear models such as logistic regression and Linear SVM. Finally we opted powerful sophiticated models such as Random Forests and GBDTs. Our final submission for the challenge was a GBDT model which received the perfect 100% score (Recall was the metric used)  on the test data. 

For a brief about the problem statement: https://www.hackerearth.com/challenges/hiring/novartis-data-science-hiring-challenge/problems or refer Problem Statement.png in this repository. Train Data (train.csv in this repo) provied in the challenge had 21788 rows where the target variable to be predicted was MULTIPLE_OFFENSE and the Test Data (test.csv in this repo) consisted of 15903 rows without the MULTIPLE_OFFENSE column. I have added the final predictions obtained by my model in Results.csv .
