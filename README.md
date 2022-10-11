# Fairness-ML
The goal of the assignment is to select the best machine learning model from different machine learning models that have different hyper-parameters, regarding their accuracy and fairness metrics. The code to create and compare the models is written in Python language in Google Colab. From Aif360 datasets “adult” and “german” datasets are used for the project. The dataset is split to test and train sets with a ratio of 0.7 to 0.3. The chosen machine learning method is Random Forest Classification. Random Forest is an algorithm that belongs to the supervised learning technique [1]. It is a classifier that combines several decision trees on different subsets of a dataset and averages the results to increase the dataset's predicted accuracy [1]. 5-fold cross-validation is used in each task. The goal of using k-fold is to use a limited sample for generating predictions on data that was not utilized during the training of the model. For both RFC and k-fold Sklearn library is used. In total there are three tasks. The first one aims to use the RFC model and by varying the trade-off hyperparameters select a model with the highest accuracy and the model with the best fairness metric from the 5 folds. For the second task, an algorithmic fairness method is applied to the system. In ML fairness relates to numerous initiatives to correct algorithmic bias in ML models’ decision-making systems. For this task, Reweighing which is a preprocessing model, and Exponentiated Gradient Reduction which is an in-processing model are used separately and the results are shown. For the third task, model selection strategies are created and after applying the models to train set from their outputs the model with the best results is revealed. After each task, the model that has the highest accuracy and best fairness metrics at the same time is found and is tested on the test dataset. The results of the applied models on the test set are obtained. Every model’s results are shown in detail in a Pandas Data Frame.
