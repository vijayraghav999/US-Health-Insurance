# **Prediction of Insurance premium charges**  
The venerable insurance industry is no stranger to data driven decision making. Yet in today's rapidly transforming digital landscape, Insurance is struggling to adapt and benefit from new technologies compared to other industries, even within the BFSI sphere (compared to the Banking sector for example.) Extremely complex underwriting rule-sets that are radically different in different product lines, many non-KYC environments with a lack of centralized customer information base, complex relationship with consumers in traditional risk underwriting where sometimes customer centricity runs reverse to business profit, inertia of regulatory compliance - are some of the unique challenges faced by Insurance Business. This context is taken directly from kaggle. 

#### -- Project Status: [Completed]  

### **Dataset**
For this project, I used public dataset available at Kaggle. Here is [link](https://www.kaggle.com/datasets/teertha/ushealthinsurancedataset). .

### **Methods Used**
* Machine Learning
* EDA
* Feature Encoding
* Model Selection

### **Technologies**
* Python
* Numpy
* Pandas
* Sklearn, jupyter


### **Description**

This dataset contains 1338 rows of insured data, where the Insurance charges are given against the following attributes of the insured: Age, Sex, BMI, Number of Children, Smoker and Region. There are no missing or undefined values in the dataset. Our objective is to predict insurance premium charges and also to explore data.

### **Steps to build this Project**
* Import the packages
* Load the data
* Data Exploration
* Splitting train data into training and validation sets.
* feature encoding
* Train and validate different models
* Test the model with test dataset
* Finalise the best model

### **Results**
* Random Forest is the best model with mean absolute error of 2400 dollars.
* The Accuracy on test dataset is 85%.
* Go through my jupyter notebook for more clear explanation.
