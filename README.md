# Customer-Chrun-Data-Analysis


#Executive Summary
This report describes the process of developing a machine learning model to predict customer churn for a telecommunications company. The goal of this project is to identify the factors that are associated with churn and to build a predictive model that can be used to identify customers who are at risk of leaving.
We used a dataset provided by the company, which contains information on the company's customers, including demographic information, service usage, and payment history. We preprocessed the data, identified the factors that are associated with churn, and built a predictive model using logistic regression.
Our analysis showed that the most important factors associated with churn are monthly charges, contract type, and internet service. Our model achieved an accuracy of 79% and can be used to identify customers who are at high risk of leaving.
Based on these results, we recommend that the company consider offering discounts to customers with high monthly charges, and to focus on retaining customers with long contract periods and high-speed internet service.
Introduction
The telecommunications industry is highly competitive, and customer churn is a major concern for many companies. Churn, which refers to customers leaving the company, can have a significant impact on revenue and profitability. Therefore, it is important for companies to identify the factors that are associated with churn and to develop strategies to retain customers.
The goal of this project is to develop a machine learning model to predict customer churn for a telecommunications company. The model will be based on a dataset provided by the company, which contains information on the company's customers, including demographic information, service usage, and payment history.
#Methodology

##Data Collection
 
The data for this project was provided by the telecommunications company. The dataset contains information on the company's customers, including demographic information (such as age, gender, and education level), service usage (such as internet service and monthly charges), and payment history (such as payment method and contract type).

##Data Preprocessing

Before building the predictive model, we preprocessed the data to address missing values which was in from of white spaces , convert categorical variables to numerical values, and drop unnecessary columns. We also performed exploratory data analysis to identify the factors that are associated with churn. To find out the reason behind the loss.

##Feature Engineering

Based on the exploratory data analysis, we identified the following factors as potentially important for predicting churn:
Monthly charges Contract type Internet service Payment method Tenure
We used these factors to build a logistic regression model to predict churn.

##Results

Our analysis showed that the most important factors associated with churn are monthly charges, contract type, and internet service. Customers with high monthly charges and those with month-to-month contracts or no contract are more likely to churn. Customers with high-speed internet service are less likely to churn.
Our logistic regression model achieved an accuracy of 78% on the testing data, which indicates that it is a good predictor of churn and as per the business problem we put Threshold value as per the requirement for your model.

##Conclusion

Based on our analysis, we recommend that the company consider offering discounts to customers with high monthly charges, and to focus on retaining customers with long contract periods and high-speed internet service. Our logistic regression model can be used to identify customers who are at high risk of leaving and to develop targeted retention strategies.
This project demonstrates the value of data science in helping companies to identify and address business challenges, such as customer churn. By leveraging the power of data and machine learning, companies can gain insights into their customers and develop strategies to improve customer satisfaction and retention.
