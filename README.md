# Comparison_of_Supervised_ML


This work attempts to replicate the work done by Caruana and Niculescu-Mizil in their 2006 paper titled “An Empirical Comparison of Supervised Machine Learning Algorithms” and analyzes the binary classification performance of three supervised learning algorithms over four different datasets (Caruana and Niculescu-Mizil). The algorithms described and used in this paper are Logistic Regression, Random Forests, and k-Nearest Neighbors.  The optimal hyperparameters for each algorithm are found by tuning different sets of hyperparameters by grid searches, based on the three scoring metrics - accuracy, ROC Area under Curve and F-score. The results of this paper are consistent with Caruana’s 2006 analysis (referred to as CNM06) that random forests have the overall best average performance over three metrics and four datasets of different balances as compared to Logistic Regression and k-Nearest Neighbors. We also observe that random forests and k-Nearest neighbors performed similarly across the four problem sets when compared across the three metrics.  
