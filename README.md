# Imbalanced-Classification
In this notebook, I have provided my approach to a highly imbalanced classification problem. 
This training data contains a matrix of anonymized and scaled features [x1, x2, x3, … , z5]. The final column “label” is the target label
for the preceding features. There are 3 labels [1, 2, 3], hence making the problem a multiclass one. The classification is carried out in 
two ways: 1) the weights of labels are equal, and 2) weight of labels is different (i.e. correct classification of label 3 is more important
than label 2, and so.

In order to address this problem, I have carried out a comprehensive exploratody data analysis and feature engineering. I have proposed an
approach based on SMOTE to handle the imbalanced problem. I have developed three classifiers, namely Adaboost, Random Forest and KNN to
conduct the classification task.
