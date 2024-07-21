# Tumor Disease Detection
This project focuses on detecting tumor diseases by employing feature selection techniques such as Mutual Information and Chi-Square Test. Various machine learning algorithms were implemented to analyze the impact of feature selection on detection accuracy.

# Introduction
The early detection of tumors can significantly improve patient outcomes. This project aims to enhance the accuracy of tumor detection by selecting the most relevant features using Mutual Information and Chi-Square Test. We implemented various machine learning algorithms to classify tumors and evaluated the impact of feature selection on their performance.

# Feature Selection Techniques
Feature selection is a crucial step in building effective machine learning models. In this project, we used the following techniques:

# Mutual Information
Mutual Information measures the dependency between variables. It helps in identifying the most informative features for the target variable.

# Chi-Square Test
The Chi-Square Test is used for testing relationships between categorical variables. It evaluates whether the observed frequencies in the contingency table differ significantly from the expected frequencies.

# Machine Learning Algorithms
We implemented and compared the following machine learning algorithms:

Decision Trees: 
A non-parametric supervised learning method used for classification and regression.
Random Forests: 
An ensemble method that operates by constructing multiple decision trees during training and outputting the mode of the classes.
Logistic Regression: 
A statistical model that in its basic form uses a logistic function to model a binary dependent variable.
Naive Bayes: 
A family of simple probabilistic classifiers based on applying Bayes' theorem with strong independence assumptions.
Support Vector Machine (SVM): A supervised learning model that analyzes data for classification and regression analysis.
K-Nearest Neighbors (KNN): A non-parametric method used for classification and regression, which predicts the labels based on the k closest training examples in the feature space.
Dataset
The dataset used in this project contains features related to tumor characteristics. Each instance in the dataset represents a tumor case with various attributes such as size, texture, and shape, along with a label indicating whether the tumor is benign or malignant.

Implementation
The implementation involves the following steps:

Data Preprocessing:

Handling missing values
Normalizing the features
Splitting the dataset into training and testing sets
Feature Selection:

Applying Mutual Information and Chi-Square Test to select the most relevant features
Model Training:

Training Decision Trees, Random Forests, Logistic Regression, Naive Bayes, SVM, and KNN models on the selected features
Model Evaluation:

Evaluating the models using metrics such as accuracy, precision, recall, and F1-score
Analyzing the impact of feature selection on the models' performance
# Results
The results section presents the performance of each machine learning algorithm before and after applying feature selection techniques. We provide detailed comparisons in terms of accuracy, precision, recall, and F1-score to highlight the effectiveness of feature selection in improving tumor detection accuracy.

# Conclusion
The project demonstrates that feature selection techniques like Mutual Information and Chi-Square Test can significantly enhance the performance of machine learning models in tumor detection. By selecting the most informative features, we can improve the accuracy and reliability of the predictions.



