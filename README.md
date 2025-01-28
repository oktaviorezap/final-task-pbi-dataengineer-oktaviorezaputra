# Rakamin Project-Based Internship : Bank BTPN Syariah
1. **Project Background**
2. **Dataset Description**
3. **Determine Best Model**
4. **Prediction Result**
5. **Business Impact Analysis Implementation**
6. **Business Recommendation (Based On Prediction Result)**
7. **Prediction Result Conclusion**

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
![image](https://github.com/user-attachments/assets/791d72f2-004a-4fb0-bb4a-068fcb4cc653)

<br>

**Model Selection Conclusion:**
The best model:

- `CatBoost`: Recall training and testing are quite balanced, no indication of overfitting or underfitting.
- `XGBoost Classifier`: Very good performance with a fairly small difference between training and testing.

# Prediction Result
Full Code: [Full Python Code - Churn (Attrited) Customer Prediction BTPN Syariah](https://github.com/oktaviorezap/final-task-pbi-dataengineer-oktaviorezaputra/blob/main/(Full_Code)_OKTAVIO_REZA_PUTRA_TASK_5_DATA_ENGINEER_VIX_BTPNS.ipynb)
<br>

<br>**Churn (Attrited) Customer before Predicted:**
<br>![image](https://github.com/user-attachments/assets/97d9c391-3064-4b71-af58-f1e4e00ebf7c)
<br>

<br>**Churn (Attrited) Customer after Predicted (Catboost Classifier):**
<br>![image](https://github.com/user-attachments/assets/73e13a67-a7d7-4d56-a31b-f4f4c383cef9)

# Business Recommendation (Based on Prediction Result)
1. **Leverage Customer Profiles for Personalized Strategies**
   - **Strategy**: Utilize detailed customer attributes such as Age, Gender, Education Level, Marital Status, and Income Category to segment customers and offer tailored financial solutions.
   - **Actions**:
       - Young Customers (Under 30): Offer financial literacy programs and credit-building tools to attract and retain younger demographics. Create targeted campaigns for first-time credit card users.
       - Higher-Income Categories: Introduce exclusive benefits like higher credit limits, premium cards (e.g., Platinum), and personalized relationship management services.
       - Dependent Count & Marital Status: Design family-oriented credit products for married customers or those with dependents, such as joint accounts or cashback on family-related expenses.
         
2. **Address Churn Indicators from Behavioral Data**
   - **Strategy**: Use behavioral metrics such as Months_Inactive_12_mon, Contacts_Count_12_mon, and Avg_Utilization_Ratio to identify at-risk customers.
   - **Actions**:
       - Inactivity Management: For customers with low activity (high Months_Inactive_12_mon), provide incentives like additional rewards points or exclusive offers to encourage engagement.
       - Engagement Improvement: Increase contact frequency with customers who have low Contacts_Count_12_mon by sending reminders, personalized offers, and relationship manager outreach.
       - Utilization Monitoring: Identify customers with very high utilization ratios and offer financial counseling or balance transfer options to avoid default risks.

3. **Improve Product Offerings Based on Card Usage**
   - **Strategy**: Analyze Card_Category, Total_Trans_Amt, and Total_Trans_Ct to understand spending habits and tailor products accordingly.
   - **Actions**:
       - Customers with high Total_Trans_Amt and high Total_Trans_Ct: Offer premium credit card upgrades with higher rewards or cashback to incentivize retention.
       - Customers with low Total_Trans_Amt: Provide targeted offers like no annual fees for low-spend customers or cashback on specific categories (e.g., groceries, dining).
         
4. **Optimize Credit Policies**
   - **Strategy**: Leverage credit-related metrics like Credit_Limit, Total_Revolving_Bal, and Avg_Open_To_Buy to optimize credit offerings and reduce risk.
   - **Actions**:
       - Customers with low Avg_Open_To_Buy and high Total_Revolving_Bal: Provide financial counseling and balance restructuring offers to reduce credit stress.
       - Customers with low Credit_Limit: Offer targeted credit limit increases based on spending patterns and credit history to encourage higher engagement.

5. **Boost Customer Relationships**
   - **Strategy**: Use Total_Relationship_Count and Months_on_book to evaluate customer tenure and product engagement.
   - **Actions**:
       - For customers with low Total_Relationship_Count: Cross-sell additional financial products such as savings accounts, insurance, or loans to deepen engagement.
       - For long-tenure customers (high Months_on_book): Reward loyalty with exclusive benefits like reduced fees, higher interest on savings, or personalized investment advisory.

6. **Proactively Manage Attrited Customers**
   - **Strategy**: Analyze Status and idstatus to understand patterns among attrited customers and design proactive retention strategies.
   - **Actions**:
       - Identify common traits among attrited customers (e.g., low Total_Trans_Ct or high Months_Inactive_12_mon) and target similar profiles with preventive retention campaigns.
       - Offer incentives for reactivation, such as cashback or fee waivers, to recently attrited customers.

7. **Enhance Digital Engagement**
   - **Strategy**: Use data-driven insights to promote digital banking features and improve customer experience.
   - **Actions**:
       - Provide app-based tracking for metrics like Total_Revolving_Bal and Avg_Utilization_Ratio to increase customer awareness of their credit usage.
       - Create gamified features in the banking app to reward activity, such as badges for low utilization or frequent transactions.

8. **Monitor and Improve Credit Utilization**
   - **Strategy**: Closely track Avg_Utilization_Ratio to identify risky credit behaviors.
   - **Actions**:
       - For customers with high utilization (>70%), offer financial planning tools, balance transfer options, or personalized repayment plans to ease credit stress.
       - Encourage low utilization (<30%) customers to explore additional products, such as loans or investments, to boost engagement.

9. **Develop a Rewards System**
    - **Strategy**: Build loyalty by introducing a rewards system tied to metrics like Total_Trans_Ct and Months_on_book.
    - **Actions**:
        - Offer tiered rewards based on transaction volume and tenure, such as higher cashback rates for longer-term customers.
        - Introduce exclusive offers for frequent spenders, such as bonus points for reaching transaction milestones.

10. **Utilize Predictive Analytics for Proactive Retention**
    - **Strategy**: Continuously use predictive churn models to identify and mitigate potential attrition risks.
    - **Actions**:
        - Develop dashboards for real-time monitoring of churn-related metrics, such as inactivity, low utilization, or low engagement.
        - Implement machine learning models to provide early alerts for at-risk customers and deploy automated outreach campaigns.


