# Shopping Trends Dataset

## Overview
This repository contains a dataset named `shopping_trends.csv`, which includes detailed information about customer purchases. It can be used for analyzing consumer behavior, exploring sales trends, and building machine learning models for customer segmentation or prediction.



## File Details

### **shopping_trends.csv**

The dataset includes the following columns:

1. **Customer ID**: Unique identifier for each customer.
2. **Age**: Age of the customer.
3. **Gender**: Gender of the customer (e.g., Male, Female, etc.).
4. **Item Purchased**: Name of the item purchased.
5. **Category**: Category of the purchased item (e.g., Electronics, Fashion, etc.).
6. **Purchase Amount (USD)**: Total amount spent by the customer.
7. **Location**: Location of the customer.
8. **Size**: Size of the purchased item (if applicable).
9. **Color**: Color of the purchased item.
10. **Season**: Season during which the purchase was made (e.g., Winter, Summer).
11. **Review Rating**: Customer's rating for the purchase (e.g., 1-5 stars).
12. **Subscription Status**: Whether the customer is an active or inactive subscriber.
13. **Payment Method**: Method used for the transaction (e.g., Credit Card, PayPal).
14. **Shipping Type**: Shipping option chosen by the customer.
15. **Discount Applied**: Discount amount applied to the purchase.
16. **Promo Code Used**: Whether a promo code was applied (True/False).
17. **Previous Purchases**: Count of previous purchases made by the customer.
18. **Preferred Payment Method**: The most frequently used payment method by the customer.
19. **Frequency of Purchases**: Frequency of purchases made by the customer (e.g., Weekly, Monthly).


**Applications**

Exploratory Data Analysis: Understand shopping patterns and trends.
Customer Segmentation: Identify high-value customers.
Sales Forecasting: Predict sales trends using historical data.
Marketing Insights: Analyze the effectiveness of discounts and promo codes.

**Continuous Variables:**

These columns contain numerical data with measurable, continuous values:

Age: Continuous, as it is a numerical measure that can take any value within a range.
Purchase Amount (USD): Continuous, representing monetary amounts.
Discount Applied: Continuous, as it represents a numerical value for discounts.
Previous Purchases: Continuous, counting the number of past purchases.
Frequency of Purchases: Could be considered continuous if treated as a frequency rate.

**Categorical Variables:**

These columns represent categories or labels:

Gender: Categorical, representing distinct groups (e.g., Male, Female).
Item Purchased: Categorical, as it contains unique items (non-numerical).
Category: Categorical, with labels like Electronics, Fashion, etc.
Location: Categorical, representing customer locations.
Size: Categorical, containing groups like Small, Medium, Large.
Color: Categorical, representing item colors.
Season: Categorical, representing distinct seasons (e.g., Summer, Winter).
Subscription Status: Categorical, with values like Active, Inactive.
Payment Method: Categorical, representing payment modes (e.g., Credit Card).
Shipping Type: Categorical, representing shipping options (e.g., Standard, Express).
Promo Code Used: Categorical, as it is a Boolean (True/False).
Preferred Payment Method: Categorical, representing the most used payment mode.  

**Sequential/Ordered Variables:**

These columns have a meaningful order (ordinal variables):

Review Rating: Ordered, as higher ratings (1-5) indicate better feedback.
Size: Can be considered ordered (e.g., Small < Medium < Large) if sizes have a progression.
Frequency of Purchases: If expressed as discrete intervals (e.g., Weekly < Monthly < Quarterly), it becomes ordered.

**Unordered Variables:**

These columns have no inherent sequence:

Gender: Unordered, as there's no natural ranking.
Color: Unordered, as color names have no ranking.
Category: Unordered, unless you assign priority levels (e.g., Electronics > Groceries).

**Summary:**

**Continuous Columns:**

Age, Purchase Amount (USD), Discount Applied, Previous Purchases, Frequency of Purchases (if numeric).
    
**Categorical Columns:**

Gender, Item Purchased, Category, Location, Size, Color, Season, Subscription Status, Payment Method, Shipping Type, Promo Code Used, Preferred Payment Method.

**Ordered Columns:**

Review Rating, Size (optional), Frequency of Purchases (if ordinal).  

**Unordered Columns:**

Color, Category, Location, Gender.
    
This breakdown helps in determining how to preprocess the data for tasks like machine learning, where numerical and categorical data require different handling strategies.







