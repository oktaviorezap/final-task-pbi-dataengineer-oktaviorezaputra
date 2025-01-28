# Rakamin Project-Based Internship : Bank BTPN Syariah
1. **Project Background**
2. **Dataset Description**
3. **Determine Best Model**
4. **Prediction Result (3 Model Algorithms)**
5. **Business Impact Analysis Implementation**
6. **Prediction Result Conclusion**

# Project Description

<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

<div class="container">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSjX98UjVYvXDrRnw0caxlGyzVgHSW9JYJ_Vw&s">
    <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjvnMeBV7QG7wIrSSIQ-ijcs9qF4Pby9QCGePJxenQsdOca8YP5OYfAWOHumLBTWsxDUuqKLKo43Ch6vJMNnDXtjRANIMVYhTYBspzGujFjzjBY1-3NQMHDb_t-b-y9CrFKu-p3hqpQMIpAKUJgBzGBL-_8M4cSXGrYPZA856iiq3CU25OvNhWGKe2o/s320/GKL11_BTPN%20Syariah%20-%20Koleksilogo.com.jpg">
</div>

</body>
</html>

<br>

**This Final Project is part of the Project-Based Internship by Rakamin Academy x BTPN Syariah Banking Company**

- **Project Background**
  - The bank’s management has observed an increasing number of customers discontinuing their credit card services, which has raised significant concerns.
  - Customer attrition not only impacts the bank's revenue but also affects its reputation and market position.
  - This trend has become a pressing issue that requires immediate attention to mitigate the negative impact on the business.
  - The manager is particularly concerned about the lack of insights into why customers are leaving and how to prevent this trend.
  - Understanding the factors driving customer churn is critical to developing effective strategies to enhance customer satisfaction and retention.
<br>

- **Project Objective**
  - The primary goal of this project is to analyze customer data and identify profiles of clients who are likely to discontinue their credit card services
  - By leveraging data-driven insights, the bank aims to proactively address the root causes of customer dissatisfaction.
  - **The objective** is to equip the management team with actionable information, enabling them to reach out to at-risk customers, offer personalized solutions, and improve overall service quality.
  - This initiative seeks to minimize customer churn and foster long-term customer loyalty, ultimately contributing to the bank’s sustained growth and competitive advantage.

# Dataset Description
- `CLIENTNUM`: Unique identification number for each customer.
- `idstatus`: The status ID of the customer, possibly referring to a specific status (e.g. active and inactive).
- `Status`: The status of the customer (e.g. Existing Customer and Attrited Customer).
- `Customer_Age` : The age of the customer.
- `Gender`: The gender of the customer (e.g Male and Female).
- `Dependent_count` : The number of dependents of the customer (The number of family members who are dependents).
- `Educationid`: The customer's education level ID, which can refer to a specific education category.
- `Education_Level`: The customer's education level (e.g. High School, Undergraduate, Graduate, etc).
- `Maritalid`: The customer's marital status ID, usually indicating the marital status (e.g. Married, Single, etc).
- `Marital_Status`: The marital status of the customer (e.g Married, Single, etc).
- `Income_Category`: The income category of the customer divided by income range .
- `card_categoryid`: The customer's card category ID, which indicates the type of card they have (e.g., credit card, debit card).
- `Card_Category`: The type of card owned by the customer (e.g., Blue, Silver, Gold and Platinum).
- `Months_on_book`: The length of time (in months) the customer has been registered or a customer (e.g., duration since joining).
- `Total_Relationship_Count`: The number of customer relationships with the company, which can refer to the number of products or services owned.
- `Months_Inactive_12_mon`: Number of months in the last 12 months
- `Contacts_Count_12_mon`: Number of contacts with the bank in the last 12 months.
- `Credit_Limit`: The credit limit given to the customer.
- `Total_Revolving_Bal`: The total unpaid balance on the credit card.
- `Avg_Open_To_Buy`: The average limit available for use on the credit card.
- `Total_Trans_Amt`: The total amount of money the customer transferred.
- `Total_Trans_Ct`: The total number of transactions made by the customer.
- `Avg_Utilization_Ratio`: Utilization Ratio in banking companies refers to a metric that calculates how much of the total available credit is actually used by a customer at a given time. It is an important measure that helps banks in evaluating the way credit is utilized by their customers. In general, this ratio is calculated as the percentage of credit used compared to the total credit approved.
# Determine The Best Model
![image](https://github.com/user-attachments/assets/4b7f575b-42d1-4d25-9d70-bfffc4e1dd9d)

<br>

**Model Selection Conclusion:**
The best model:

- `CatBoost`: Recall training and testing are quite balanced, no indication of overfitting or underfitting.
- `XGBoost Classifier`: Very good performance with a fairly small difference between training and testing.

# Project Result
Full Code: [Full Python Code - Churn (Attrited) Customer Prediction BTPN Syariah](https://github.com/oktaviorezap/final-task-pbi-dataengineer-oktaviorezaputra/blob/main/(Full%20Code)%20OKTAVIO_REZA_PUTRA_TASK_5_DATA_ENGINEER_VIX_BTPNS.ipynb)
<br>

<br>**Churn (Attrited) Customer before Predicted:**
<br>![image](https://github.com/user-attachments/assets/97d9c391-3064-4b71-af58-f1e4e00ebf7c)
<br>

<br>**Churn (Attrited) Customer after Predicted (Catboost Classifier):**
<br>![image](https://github.com/user-attachments/assets/73e13a67-a7d7-4d56-a31b-f4f4c383cef9)

<br>**Churn (Attrited) Customer after Predicted (XGBoost Classifier):**
<br>![image](https://github.com/user-attachments/assets/738cd909-9fe5-4542-840e-bd3247c032c3)

<br>**Churn (Attrited) Customer after Predicted (Gradient Boosting Classifier):**
<br>![image](https://github.com/user-attachments/assets/693dd269-14ab-4608-a420-e925fb81d7d8)


