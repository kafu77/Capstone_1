# Capstone Project:
The capstone project is a demonstration of the abilities developed in a professional Machine Learning and Artificial Intelligence program to answer a question of interest using various tools. The project follows the CRISP-DM methodology, a widely-used process for data mining that includes six phases: Business Understanding, Data Understanding, Data Preparation, Modeling, Evaluation, and Deployment.

# CRISP-DM FARMWORK:
1. Business Understanding:
Goal: The goal of the project is to develop regression models and compare them to select the best model to help residential home buyers in Ames, Iowa predict an affordable sale price for their dream house. The project involves training models on original feature data and log-transformed targets, comparing results, and making a model recommendation for home buyers.
2. Data Understanding:
To handle missing values, several imputation techniques are used such as replacing missing values with the median value of the respective feature, creating a new category called "NA" for missing values, and imputing missing values based on the most correlated feature. Additionally, some features are transformed into numerical features, and some categorical features are one-hot encoded. After the data preparation phase, exploratory data analysis (EDA) is conducted to gain insights into the data, such as identifying outliers and examining the relationships between variables.

3.Data Preparation:
The data preparation step involves organizing the data into a structured form, resolving structural errors, removing and correcting data that are incorrect, corrupt, or duplicate. This step is the heavy lifting task and takes up almost 80% of the project. Removing outliers is also a part of data preparation, which helps to improve model performance. In this project, exploratory data analysis was performed, and data was cleaned by removing outliers.

4. Modeling:
The Modeling phase involves training and testing machine learning regression models to choose the best one to solve a business problem. Categorical features are encoded using the dummies method, and a dimensionality reduction technique called PCA is applied to reduce the number of features. PCA is chosen for its computational efficiency, effectiveness with large datasets, and speed. Only 10 components are used due to limitations in computer processing power.

# Results:
Both the Ridge model and the Linear Regression model have smaller errors than the baseline model. However, the Ridge model has a much smaller error than the Linear Regression model, and it is also much faster.

# Work will add on the final capstone: 
1. Apply feature Engineering to tranform a catogerical data into numerical
2. Add Gradient Base Regressor and Random Forest Regressor model
3. Comparing result of new model and previous models
4. Apply a TranformTarget model and choose the best
5. Recommend the best model




