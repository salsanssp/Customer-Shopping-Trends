# Customer-Shopping-Trends

## **Business Understanding**

**Background:**

The retail store data reflects information about purchases made by a number of customers. This is valuable data for conducting analyses on purchasing preferences, consumer behavior, seasonal trends, as well as the effectiveness of promotional programs and discounts. By analyzing this data, companies can make better decisions regarding product stock, marketing strategies, and customer service.

**Business Question:**

1. In which season do customers make the most purchases?

2. How do Review Ratings for clothing vary based on their categories?

3. What is the count of customers for each type of shipping?

4. Who are the most frequent buyers based on gender?

5. Which payment method is most commonly used by male buyers?

## **Data Understanding**

Source data: https://www.kaggle.com/datasets/iamsouravbanerjee/customer-shopping-trends-dataset

The dataset has 19 columns and 3900 rows.

Data Dictionary:

* Customer ID - Unique identifier for each customer

* Age - Age of the customer

* Gender - Gender of the customer (Male/Female)

* Item Purchased - The item purchased by the customer

* Category - Category of the item purchased

* Purchase Amount (USD) - The amount of the purchase in USD

* Location - Location where the purchase was made

* Size - Size of the purchased item

* Color - Color of the purchased item

* Season - Season during which the purchase was made

* Review Rating - Rating given by the customer for the purchased item

* Subscription Status - Indicates if the customer has a subscription (Yes/No)

* Shipping Type - Type of shipping chosen by the customer

* Discount Applied - Indicates if a discount was applied to the purchase (Yes/No)

* Promo Code Used - Indicates if a promo code was used for the purchase (Yes/No)

* Previous Purchases - The total count of transactions concluded by the customer at the store, excluding the ongoing transaction

* Payment Method - Customer's most preferred payment method

* Frequency of Purchases - Frequency at which the customer makes purchases (e.g., Weekly, Fortnightly, Monthly)

## **Data Preparation**

* Code Used:

* Python Version: 3.11.7

* Packages: Numpy, Matplotlib, Seaborn, Pandas.

## **Data Cleansing**

![image](https://github.com/Vanz92x/Customer-Shopping-Trends/assets/165736197/f6c95ca6-9b7f-4083-b5c8-d3c47053d91a)

The table above shows that there are **no missing values** and **all column data types are appropriate.**

## **EDA (Exploratory Data Analysis)**

### 1. In which season do customers make the most purchases?
<div align="center"><img src="https://github.com/Vanz92x/Customer-Shopping-Trends/assets/165736197/4e8d6609-662d-4931-9d8d-853c36017a01" /></div>

In the diagram above, it can be seen that **in the spring season, retail shop buyers made a lot of purchases** with the number of buyers reaching 999 buyers. Meanwhile **summer is the season with the fewest retail shop buyers** making purchases with a total of 955 buyers.

### 2. How do Review Ratings for clothing vary based on their categories?

<div align="center"><img src="https://github.com/Vanz92x/Customer-Shopping-Trends/assets/165736197/6bba2927-0a37-44b6-a002-27af231151dc" /></div>

Based on the diagram above, it can be seen that each category has a review rating above 3.5. The diagram also shows that **the clothing category with the highest rating is footwear** with the highest rate at 3.76. Meanwhile **on average, buyers do the most review ratings in the outerwear category.**

### 3. What is the count of customers for each type of shipping?

<div align="center"><img src="https://github.com/Vanz92x/Customer-Shopping-Trends/assets/165736197/81f806a5-cb3e-449f-89f4-52946021e6db)" /></div>

Based on the diagram above, we can see the number of customers who use each shipping type, we can see the shipping type preferences that are most widely used among them. Free Shipping has the largest number of customers with 675 customers, which means that in this case **the majority of customers prefer the free shipping option.**

### 4. Who are the most frequent buyers based on gender?

<div align="center"><img src="https://github.com/Vanz92x/Customer-Shopping-Trends/assets/165736197/d0ff0fb4-0a3e-4211-9627-d1913cdaca7d" /></div>

Based on the diagram above, **the number of male buyers making the most purchases** is 2,652 compared to female buyers who are only half as many as male buyers, namely around 1,248 buyers with the difference between the two being around 1,404 purchases.

### 5. Which payment method is most commonly used by male buyers?

<div align="center"><img src="https://github.com/Vanz92x/Customer-Shopping-Trends/assets/165736197/887b80a6-0113-4a42-b564-3446c547ee83" /></div>

From the graph above, it can be seen that **male buyers tend to prefer using credit cards** as a payment method, with a total of 473 users. On the other hand, **the use of debit cards is less popular among male buyers**, only reached 426.

## **Summary**

* The majority of retail purchases are made during the spring season.
* Footwear are the most purchased category based on review rating.
* Male buyers dominate with a total of 2,652.
* Male buyers are more likely to use credit card payment methods.
* Many shoppers prefer shipping methods with free shipping options.
