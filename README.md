# **RFM Analysis Using Python**

### Welcome to the RFM Analysis project! This repository provides a detailed explanation of how to use Python for RFM analysis—a popular method in marketing to segment customers based on their purchasing behavior. This analysis helps businesses understand their customers' engagement, loyalty, and value based on three key metrics: Recency, Frequency, and Monetary value.

## ***Overview***
#### RFM Analysis helps answer crucial questions for businesses:
* **Recency:** How recently did the customer make a purchase?
* **Frequency:** How often do they make purchases?
* **Monetary Value:** How much money do they spend?

#### By assessing these metrics, businesses can classify customers into different segments and tailor their marketing strategies accordingly.

## ***How It Works:***

## 1. **Data Preparation**

#### We first import and clean the customer purchase data. The dataset includes customer information, purchase dates, and the amount spent.

![image](https://github.com/user-attachments/assets/c705d426-3b69-4022-9382-aa47324ec4d5)
![image](https://github.com/user-attachments/assets/22e0da15-4fda-4e2a-a74e-7129fe6a9f51)

## 2. **Calculating RFM Metrics**

#### We calculate the recency (days since the last purchase), frequency (number of purchases), and monetary value (total amount spent) for each customer.

![image](https://github.com/user-attachments/assets/badb8749-f68d-4644-8c7f-6fde96df738b)

## 3. **Assigning RFM Scores**
#### Each customer is assigned scores from 1 to 5 for recency, frequency, and monetary value. A higher recency score means a more recent purchase, and higher frequency and monetary scores reflect more frequent and larger purchases.

![image](https://github.com/user-attachments/assets/7dc9bd40-a1f3-45af-8cf3-044c5a4666a0)

## 4. **Segmenting Customers Value**
#### Based on their RFM scores, customers are segmented into three categories:
* High-Value
* Mid-Value
* Low-Value
#### This helps identify high-value customers who contribute significantly to the business.

![image](https://github.com/user-attachments/assets/0d2fa07f-27ed-4921-a557-6df6905fdd9c)
![newplot](https://github.com/user-attachments/assets/c2005f8d-768a-4946-8c30-7f5b6b12f00b)


## 5. **RFM Customer Segments**
#### It's a broader classifications based on the RFM scores. These segments, such as “Champions”, “Potential Loyalists”, and “Can’t Lose” provide a more strategic perspective on customer behaviour and characteristics in terms of recency, frequency, and monetary aspects.
![image](https://github.com/user-attachments/assets/152fde4c-b069-4db2-b96f-8c8da096e101)
![newplot(1)](https://github.com/user-attachments/assets/d3a8643a-d5e4-40ad-8e96-d20ffeca6654)

## 6. **RFM Analysis**
### * Distribution of customers across different RFM customer segments within each value segment:

![image](https://github.com/user-attachments/assets/5ea438d2-08bf-4239-8c0a-6d51a3f7118e)
![newplot(2)](https://github.com/user-attachments/assets/0cc4877b-dc77-4579-827f-4bc1e10046f8)

### * Additional Insights: A correlation matrix and a heatmap for deeper insights into the relationships between Recency, Frequency, and MonetaryValue

![image](https://github.com/user-attachments/assets/cc8c86a0-a126-4f19-9486-7ba4ffc39f22)
![newplot(3)](https://github.com/user-attachments/assets/bf234151-dbbe-4f79-a95a-8936ebbe8ed7)

### * Recency, Frequency, and Monetary scores of all the Segments:

![image](https://github.com/user-attachments/assets/54211a7a-9cff-498e-af7f-80f39da865f9)
![newplot(4)](https://github.com/user-attachments/assets/736c7876-f382-45c3-9b64-6d81b3949332)


## ***Why RFM Analysis?***
#### RFM Analysis is valuable because it allows businesses to:
* **Identify high-value customers:** These customers spend more and are likely to respond well to special offers.
* **Retain customers:** Customers with low recency can be targeted with personalized re-engagement strategies.
* **Improve marketing:** By segmenting customers, businesses can tailor their messages and promotions for better results.




