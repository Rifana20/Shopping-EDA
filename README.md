# Shopping-EDA
# 🛍️ Shopping Trends EDA

This project performs **Exploratory Data Analysis (EDA)** on a shopping trends dataset to uncover insights into customer behavior, purchasing patterns, and product popularity. Visualizations created using `Matplotlib`, `Pandas`, and `NumPy` help us understand trends more effectively.

---

## 📁 Dataset

**Filename**: `shopping_trends_updated.csv`  
The dataset includes features such as:

- Customer ID
- Age
- Gender
- Item Purchased
- Category
- Purchase Amount (USD)
- Location
- Size
- Color
- Season
- Review Rating
- Subscription Status
- Shipping Type
- Discount Applied
- Promo Code Used
- Previous Purchases
- Payment Method
- Frequency of Purchases

---

## 🧰 Libraries Used

```python
import pandas as pd
import matplotlib.pyplot as plt
import numpy as np

---

## 💡 Key Insights

- 👟 **Footwear** and 👚 **Clothing** have the highest average purchase amounts.
- 💳 **PayPal** is the most frequently used payment method.
- ⭐ **Review ratings** are fairly consistent across **seasons** and **discount statuses**.
- 📏 Size **S** products tend to be slightly more **expensive** on average.
- 🔁 Customers with more **previous purchases** tend to leave **higher review ratings**.
