This project is to predict if the customer will subscribe to a term deposit.

The dataset is heavily imbalanced and was trained on 4 models, namely Logistic Regression, Decision Tree, Random Forest and XGBoost. The models' performance indicates XGBoost as the optimal model due to its highest F1 score of **0.56** on test set, **92.8%** of train accuracy and **91.2 %** of test accuracy. Also, the optimal decision threshold is **0.52** and two most highly predictive features are `duration` and `month`.

There are **2153** customers whom the model predicts that they should have been registers but actually not. This implies that they are very likely to be a success in next calls, therefore, it is recommended to put more marketing effort into these customers.
