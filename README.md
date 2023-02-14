# Capstone Project:
This capstone project is a final project that can show the ability developed from the professional Machine Learning and Artificial Intelligent program and answer a question of interest using the various tools that have encountered. The project followed the most widely- used methodology for data mining process called a Cross-Industry Standard Process for Data Mining (CRISP-DM). The methodology provides a structured approach for planning and data mining project. The methodology has six phases Business Understanding, Data Understanding, Data Preparation, Modeling, Evaluation, and Deployment.

# CRISP-DM FARMWORK:
1. Business Understanding:
Goal: The goal of the project is to develop and compare a regression models, eventually selecting the best model that helps the residential home buyers in Ames, Iowa to predict an affordable sale price for their house dream. The project begins trained the models on the original feature data, then trained the models on the log transformed target and comparing to the original models results and give the best model recommendation for the residential home’s buyers in Ames, Iowa.
2. Data Understanding:
The data is collected online from the largest data science community and machine learning platform called Kaggle. The dataset has 81 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa and 1460 entries. Only data between 25% and 75% quartile are used. Others outside from this range are not considered. Some features has huge mising values. 

3.Data Preparation:
The data preparation step is about organizing the data into a structure form, resolving structure errors, removing, and correcting data that are incorrect, corrupt, and duplicate. This is the heavy lifting task. Almost 80% of the project is a data preparation. Removing the outliers also a data preparation part helps improving the model performance. In this data exploratory analysis, data is cleaned and removed an outliers. 

4. Modeling:
The Modeling phase is about train and test the model to select the best performed model. In this phase,a machine learning regression models have been trained, developed, and selected to answer the business problems. In this part first the categorical features are encoded using the dummies method. A dimensionality reduction (PCA) method is applied to reduce the features. PCA has been choosen, becuase this mehtod is computationally efficient, can handle large datasets effectively, and faster. However, becuase of the computer processor, only 10 components are used. 

# Results:
Even though both models have smaller error than the baseline model, the Ridge model aslo has much smaller error than Linear regression model. It also much faster than Linear Regression model. 




