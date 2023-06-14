# Bank Customer Churn Analysis with Python

This repository contains two Jupyter notebooks that perform exploratory data analysis (EDA) and model building for a bank customer churn analysis. The 
notebooks are available for cloning and corrections in this repository as `01_Exploratory_Data_Analysis.ipynb` and `Model_building.ipynb`

## Problem Statement

Customer churn is a major problem for banks. It can lead to lost revenue, increased costs, and a decline in customer satisfaction. This project aims to identify the key factors that are associated with customer churn and to develop strategies to reduce customer churn and improve customer retention.

The objectives of this project are to:

* Identify the key factors that are associated with customer churn.
* Develop strategies to reduce customer churn and improve customer retention.
* Develop and evaluate high accuracy model for prodicting churn.

The expected results of this project are:

* A list of the key factors that are associated with customer churn.
* Strategies to reduce customer churn and improve customer retention.
* A model that can reliably prodict customer churn 


## Requirements

* Python 3.6 or higher
* Jupyter Notebook
* NumPy
* Pandas
* Matplotlib.pyplot
* Seaborn
* Scikit-learn


## Dataset

The dataset used for this analysis is a CSV file that can be accessed in this repository `Churn_Modelling.csv` and it contains the following columns:

* RowNumber: Used to sort the data (1-2000)
* Customerid: The customer's ID number with bank
* Surname: The customer's last name
* CreditScore: The customer's credit score
* Geography: The customer's geographic location
* Gender: The customer's gender
* Age: The customer's age
* Tenure: The customer's length of time as a customer
* Balance: The customer's account balance
* NumOfProducts: The number of products that the customer has with the bank
* HasCreditCard: Whether or not the customer has a credit card with the bank
* IsActiveMember: Whether or not the customer is an active member of the bank
* EstimatedSalary: The customer's estimated salary
* Exited: Whether or not the customer has churned

## EDA Notebook

The EDA notebook explores the dataset and identifies key features that are associated with customer churn. The notebook also includes visualizations that help to understand the distribution of the data and the relationships between the features.

## Model Building Notebook

The model building notebook builds six different machine learning models to predict customer churn. The models are evaluated using accuracy, precision, recall, auc_roc_curve and kappa score. The random forest model achieves the best results, with an accuracy of 87% and a kappa score of 0.52.

## Usage

To run the notebooks, clone the repository and then open the Jupyter Notebook application. The notebooks can be run by clicking on the `Run` button in the top right corner of the notebook.

## Results

The results of the analysis show that the following features are most associated with customer churn:

* Geography
* Gender
* Age
* Credit score
* NumOfProducts
* Tenure

The random forest model was able to predict customer churn with an accuracy of 87%. This means that the model was able to correctly identify 87% of customers who would churn. The kappa score of 0.52 indicates that the model is doing significantly better than random chance.

## Recommendations

The results of the analysis suggest that the bank can take the following steps to reduce customer churn:

* Offer financial education and counseling to customers to help them improve their credit scores.
* Develop targeted marketing campaigns to reach customers who are most likely to churn (Expecially customers in Germany, Females and Customers with fewer products).
* Improve the customer experience by providing personalized service and making it easy for customers to do business with the bank.

## Future Work

The following are some ideas for future work on this project:

* Collect more data from customers to improve the accuracy of the models.
* Use other machine learning algorithms to predict customer churn.
* Develop a customer churn prevention program based on the results of the analysis.

## Conclusion

This project has the potential to make a significant contribution to the bank by helping to reduce customer churn and improve customer retention. The results of the project will be used to develop strategies to improve the customer experience and to make the bank more competitive.

## Contact

If you have any questions, please contact me at `kdoumu@gmail.com`
