## Customer Churn Analysis Dashboard

### Dashboard link: https://app.powerbi.com/groups/me/reports/e19a0d67-9cc3-4967-afb0-4a1b5e259f6b/ReportSection?experience=power-bi

## Problem Statement:

Customer churn is the percentage of customers who stop using a company's products or services during a certain time frame. It is a critical metric because a high churn rate can significantly impact the profitability and long-term success of a business. This analysis will help the bank deploy effective retention strategies, ultimately preserving revenue and enhancing customer satisfaction.

![image](https://github.com/user-attachments/assets/af4f7ebd-0423-42a2-bc31-97f9de1ff8d0)


### Dataset Description
The dataset consists of 10,000 customer records, each featuring demographic information, account details, and other relevant attributes that could influence a customer's decision to leave the bank. There are 14 initial attributes (or columns) for each customer, which include both identifiers and potential predictors of churn.

link to the dataset: https://www.kaggle.com/datasets/barelydedicated/bank-customer-churn-modeling

### Attributes:

RowNumber: A numerical identifier for the row in the dataset.

CustomerId: A unique identifier for each customer.

Surname: The last name of the customer.

CreditScore: A score assigned to a customer based on their credit history.

Geography: The country of the bank's branch where the customer's account is located.

Gender: The customer's gender (male/female).

Age: The customer's age in years.

Tenure: The number of years the customer has been with the bank.

Balance: The account balance maintained by the customer.

NumOfProducts: The number of banking products used by the customer.

HasCrCard: Indicates whether the customer has a credit card with the bank (1 for Yes, 0 for No).

IsActiveMember: Indicates whether the customer is considered an active member based on their account activity (1 for Yes, 0 for No).

EstimatedSalary: The estimated annual salary of the customer.

Exited: Indicates whether the customer has churned (1 for Yes, 0 for No). This is the target variable for our predictive model.

### New Measures
Female Count: The total number of female customers.

Male Count: The total number of male customers.

Total Number of Customers: The total number of customers in the dataset.

### New Columns
Age Category: Categorizes customers into different age groups.

Balance Category: Categorizes customers based on their account balance.

Credit Category: Categorizes customers based on their credit score.

These measures and columns have been created to provide more insightful analysis and visualizations in the Power BI dashboard.

From Analysis, some of key insights are:

1.Customers from Germany are significantly more likely to leave the bank compared to other regions.

2.Female customers are highly likely to churn compared to males.

3.Customers who actively make transactions have lower churn rates.


![image](https://github.com/user-attachments/assets/b89e773a-6ce8-400f-995b-eccf93f5995e)

