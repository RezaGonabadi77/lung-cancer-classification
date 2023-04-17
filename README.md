
# Lung Cancer Detection
This repository contains code for a lung cancer detection model that uses different machine learning algorithms.

# Dataset
The dataset used for this project contains information on various features related to lung cancer such as age, gender, smoking history, etc. The target variable is whether or not the patient has lung cancer.

# Preprocessing
Before building the classification models, the dataset was preprocessed by converting categorical features to numerical features. The data was then split into training and testing sets.

# Classification
The following machine learning algorithms were used for classification:

Logistic Regression (0.936)
Random Forest (0.954)
SVM (0.931)
Neural network (0.935)
KNN (0.89)
LDA (0.93)
Binary Tree (0.99)
Navive Bayes (0.91)
The accuracy of each model on the test set is indicated in parentheses.

# Visualization
In addition to the above classification models, the t-distributed stochastic neighbor embedding (t-SNE) algorithm was used to visualize the data in two dimensions.

# Usage
To use this code, simply clone the repository and run the lung_cancer_detection.py file. The script will preprocess the data, train the different classification models, and output the accuracy of each model on the test set.

# Dependencies
This code requires Python 3 and the following libraries:

scikit-learn
pandas
matplotlib
seaborn
Credits
This project was completed by Reza Gonabadi as part of Personal Project. The dataset used for this project was obtained from Kaggle.com.

Feel free to modify this template to better suit your needs and add any additional information that you think would be helpful for users who are interested in your project. Good luck!
