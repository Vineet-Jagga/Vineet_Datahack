# Vineet_Datahack
Steps performed:
1)Load, merge, and split data into features (X) and targets (y) for training and testing.
2)Build preprocessing pipelines for numerical (imputation, scaling, PCA) and categorical features, and combine them into a single preprocessor.
3)Employ a multi-output XGBoost classifier with L1/L2 regularization, integrated into a pipeline with the preprocessor. Train the model on the training set.
4)Validate the model's effectiveness by predicting on a held-out validation set and calculating the mean ROC AUC as the performance metric.
5) Utilize the trained model to generate predictions for the test set, saving the results (probabilities of receiving each vaccine) in a "prediction.csv" file.
