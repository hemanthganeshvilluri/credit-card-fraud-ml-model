The code represents a Machine Learning Classification Model (Credit Card Fraud Detection).
->  The model is developed using dataset (creditcard) from kaggle.
Main Tools and Libraries used in this model are:
   ->  Pandas  (for representing and handling data)
   ->  Numpy  (used for mathematical and statistical problems)
   ->  Matplotlib  (used for plotting and visualization)
   ->  seaborn  (used for visualization)
   ->  scikit-learn  (ML library for python)
   ->  imblearn  (contains balancing techniques for imbalanced datasets)
Things i have learned when preparing the model:
   -> i got to understand about class imbalance and learnt how to balance it.
   -> i learned that, instead of using default parameters of the model, it is better to use GridSearchCV (which is for hyperparameter tuning)
   -> it is important to understand that, for imbalanced models such as these, it is best to evaluate the model with recall, f1 score and auc_roc instead of accuracy.
Note:I haven't used any pipelines for the model as it is my first model and i haven't yet deployed the model.
