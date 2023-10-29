## Medical Insurance Price Prediction 
This project is designed to predict Medical Insurance Prices using Machine Learning techniques. The "Predictive Modelling for Medical Insurance Premiums" is a data science project aimed at utilizing advanced data analytics and machine learning techniques to enhance the accuracy of predicting medical insurance premiums for individuals. This project seeks to address the need for more precise pricing models in the medical insurance industry, thereby benefiting both insurance providers and policyholders.
## Project Description
## Problem Statement
The problem at hand is the inaccuracy and lack of transparency in estimating medical insurance premiums. The current methods for determining these premiums often rely on historical claims data and broad actuarial calculations.
Best Possible Solutions
Three primary approaches are considered for solving this problem:
1.	Doctor And Insurance Experts : Utilizing domain knowledge from Doctor and Insurance Experts.
2.	Intuition About Medical Insurance : Intuition-based pricing.
3.	Using Machine Learning: Employing data-driven machine learning techniques.
## Introduction About Project
The "Predictive Modelling for Medical Insurance Premiums" is a data science project aimed at utilizing advanced data analytics and machine learning techniques to enhance the accuracy of predicting medical insurance premiums for individuals. This project seeks to address the need for more precise pricing models in the medical insurance industry, thereby benefiting both insurance providers and policyholders.
## Tools and Libraries
## Tools
•	Python
•	Jupyter Notebook
•	Flask
•	HTML
•	CSS
•	JavaScript
•	Heroku
•	GitHub
## Libraries
•	Pandas
•	Scikit-Learn
•	Numpy
•	Seaborn
•	Matplotlib
## Data Collection
For this project, we utilized data available on Kaggle. The dataset contains 7 columns and 1338 rows, featuring key information about the properties ,
•	age    
•	sex    
•	bmi
•	children  
•	smoker    
•	region    
•	charges
Project Flow
## Exploratory Data Analysis (EDA)
## Data Cleaning
We started with 7 columns but removed unnecessary Data cleaning included:
•	Handling missing values
•	Removing corrupted data
•	Date and text parsing
## EDA
Exploratory Data Analysis (EDA) is a critical initial step in the data analysis process. It involves investigating, summarizing, and visualizing the main characteristics of a dataset. EDA helps you understand your data, identify patterns, relationships, anomalies, and insights, which are crucial for making informed decisions and formulating hypotheses for more advanced analyses.
## Data Collection and Inspection:
Gather the dataset you intend to analyse.	
Inspect the data to ensure it's in a usable format.
Check for missing values, duplicates, and outliers
## Feature Engineering
We discovered outliers in a bmi column applied the IQR method for outlier removal. 
We have replaced outliers with upper_tail , now dataset having no outlier checked from using seaborn library.
## Data Normalization
We used min-max normalization to scale numerical features between 0 and 1.
## .Encoding
We have applied label encoding by using Label Encoder. Which have replace all the categorical dataset into 0 and 1 format.
Separating Independent and Dependant Variables
We have separated independent and dependant variables. Here dependant variable is charges. 
Choosing the Best ML Model
We explored multiple machine learning models, including Linear Regression, logistic regression.
Model Creation
Linear Regression as the best-performing model with 90% accuracy on test data after hyperparameter tuning. The model was saved using pickle.
## Model Deployment
The model was integrated into a user-friendly web interface using HTML, CSS, and Flask.
## Model Conclusion
The model predicts housing prices with 79% accuracy on test data.
## Project Innovation
•	User-friendly
•	Open source
•	High accuracy
•	GUI-based application
## Limitations and Next Steps
## Limitations:
•	Lack of a mobile application
•	Potential for further accuracy improvements
•	Large model size (~310MB)
•	Limited feature set
## Next Steps:
•	Develop a mobile application
•	Reduce model size using Principal Component Analysis (PCA)

