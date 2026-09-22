# 💳 Credit Card Customer Behavior and Financial Analysis

Exploratory Data Analysis (EDA) and data cleaning on credit card customer behavior using Python and Pandas.

## 🛠️ **Technologies Used**
* **Python** (Main programming language)
* **Pandas & NumPy** (Data manipulation and cleaning)
* **Matplotlib & Seaborn** (Data visualization and charting)

---

## 🧹 **Data Cleaning Steps**
Before starting the analysis, the raw dataset went through the following treatment stages:
1. **Handling Null Values:** Identification and replacement/removal of missing data in critical columns (such as credit limit and minimum payment values).
2. **Column Standardization:** Adjustment of column names and conversion of data types to ensure numerical calculations occurred without errors.
3. **Outlier Removal:** Identification of extreme values (customers with balances or purchases way outside the curve) to avoid distortions in the charts.

---

## 📊 Main Insights and Visualizations

### 1. One-off Purchases vs. Installment Purchases
<img width="534" height="429" alt="image" src="https://github.com/user-attachments/assets/8b907fcb-dd4f-41da-87a2-1c491cb7d21d" />

Analyzing the data, the average volume of one-off purchases is predominantly higher than installment purchases. Out of 8,950 records, 3,498 are one-off purchases. We could say this might be related to the credit card limit, but it is much more related to how individuals manage their money than anything else. Some data points showing consistency in one-off purchases belong to customers with higher credit limits.

### 2. Purchase Frequency: One-off vs. Installments
<img width="700" height="347" alt="image" src="https://github.com/user-attachments/assets/aeee3210-adc1-4605-a5b4-b3f0d7519caf" />

Analyzing the charts, there is a higher frequency of people who make one-off purchases. The overall average purchase frequency for these credit card customers is **0.49**, with a one-off purchase frequency of **0.20** and an installment purchase frequency totaling **0.36**.

### 3. Balance, Credit Limit, Payments, and Minimum Payments
<img width="835" height="493" alt="image" src="https://github.com/user-attachments/assets/4404cef0-7055-4b5f-bd78-f45c7c0cc787" />

Card users have an average account balance of **$1,564**, an average credit limit of **$4,494**, make an average payment of **$1,733**, and an average minimum payment of **$864**. Looking at the chart, the account balance is always much lower compared to their credit limit. Furthermore, the average amount for users who pay the minimum value is slightly lower than those who pay the full bill. This demonstrates that most users prefer to pay off the entire credit card bill at once rather than just paying the minimum amount required by banks.

---

## 🚀 How to Run the Project
1. Clone this repository:
   ```bash
   git clone [https://github.com/your-username/customer-churn-analysis.git](https://github.com/your-username/customer-churn-analysis.git)
