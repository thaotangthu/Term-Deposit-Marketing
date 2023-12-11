This project is to predict if the customer will subscribe (yes/no) to a term deposit (variable y).

The dataset is heavily imbalanced and was trained on 4 models, namely Logistic Regression, Decision Tree, Random Forest and XGBoost. The model outputs indicate XGBoost as the optimal model due to its highest F1 score of **0.56** on test set, **92.8%** of train accuracy and **91.2 %** of test accuracy. Also, the optimal decision threshold is **0.52** and two most important features that are highly predictive are `duration` and `month`.

There are **2153** customers whom the model predicts that they should have been registers but actually not. This implies that they are very likely to be a success in the next calls, therefore, it is recommended to put more marketing effort into these customers.
