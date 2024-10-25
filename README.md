# Customer-Churn-Analysis

**TOOLS USED**:  Python , PowerBI

## **PYTHON ANALYSIS**

### **Executive Summary**

This analysis focuses on identifying key factors influencing customer churn in a telecom company. Customer churn refers to the rate at which customers stop using the company's services. The analysis draws insights from demographic, account, and behavioral data, examining correlations between these factors and churn.

#### **Key Insights and Patterns**

1. **Customer Demographics & Account Information**:
   - **Tenure**:
     - Around **60%** of customers who churned had a tenure of fewer than 12 months.
     - Customers with a tenure longer than 36 months had a churn rate of only **16%**, indicating that retention strategies are more effective for long-term customers.
   - **Monthly Charges**:
     - Customers with higher monthly charges (above \$80) experienced a churn rate of approximately **45%**, compared to just **18%** for those with lower monthly charges (below \$50).
   - **Contract Type**:
     - Churn is significantly lower among customers with longer-term contracts. Customers on month-to-month contracts show a churn rate of **42%**, whereas those with one-year or two-year contracts have churn rates of **11%** and **3%**, respectively.
  
2. **Churn Analysis by Service Usage**:
   - **Internet Service**:
     - Churn rates are higher among customers with fiber optic internet service (**42%** churn) compared to those with DSL (**24%** churn), likely due to fiber customers facing higher monthly bills.
   - **Add-on Services**:
     - Customers who subscribed to additional services like tech support, streaming TV, and security had lower churn rates (**12%**), compared to those who only had basic services (**37%** churn).
  
3. **Payment Methods**:
   - Customers using electronic checks as a payment method had the highest churn rate (**46%**), compared to those using automatic bank payments (**15%**), credit cards (**22%**), and mailed checks (**19%**).
   - The convenience and predictability of automatic payments may reduce churn by preventing late or missed payments.

4. **Correlation between Key Factors and Churn**:
   - **Monthly Charges and Churn**:
     - A direct relationship was observed, with churn rates climbing steeply as monthly charges increased. Customers paying over \$90/month saw churn rates exceeding **50%**.
   - **Tenure and Churn**:
     - Tenure plays a significant role in churn. Customers in their first year are at higher risk, with **55%** of first-year customers churning, while only **20%** of those who stayed beyond three years churned.

### **Visual Insights**:
 
### 1. Churn Distribution
- **Objective:** Identify the overall churn rate by comparing the distribution of churned vs. non-churned customers.
- **Insight:** Provides a baseline understanding of churn within the dataset.

### 2. Churn by Tenure and Contracts
- **Objective:** Examine how churn rates vary by contract length and customer tenure.
- **Key Findings:** 
  - Month-to-month contracts show significantly higher churn rates compared to longer-term contracts.
  - Short-tenure customers are more likely to churn, highlighting retention opportunities in early customer stages.

### 3. Monthly Charges and Total Charges
- **Objective:** Analyze how monthly and total charges relate to churn rates.
- **Insights:** 
  - Customers with higher monthly charges exhibit higher churn rates.
  - Box plots show total charges distribution by churn status, helping pinpoint customer segments with elevated churn risk.

### 4. Customer Demographics
- **Objective:** Explore churn rates across various demographic segments, including senior citizen status and gender.
- **Key Findings:** 
  - Senior citizens are more likely to churn, providing an opportunity to tailor retention strategies for this group.
  - Gender did not have a significant impact on churn rates.

### 5. Payment Methods
- **Objective:** Identify correlations between payment method types and churn.
- **Insights:** 
  - Electronic payment methods show higher churn rates, suggesting that flexibility in payment options could reduce churn.

### 6. Correlations and Pairwise Relationships
- **Objective:** Use correlation heatmaps and pair plots to uncover relationships between numeric features and churn.
- **Key Findings:**
  - Positive correlation observed between monthly charges and churn likelihood.
  - Pair plots reveal multi-dimensional relationships between features like tenure, total charges, and monthly charges with respect to churn.

  

## **POWERBI RPORT**


# Customer Churn Analysis Report

## Overview

This report presents a comprehensive analysis of customer churn patterns, aiming to identify key factors contributing to customer attrition and potential retention strategies. Our analysis includes metrics such as churn rate by demographic features, subscription attributes, service types, and billing information, using a telecom dataset with 7,043 customers.

## Key Insights

1. **Churn Rate and Customer Demographics:**
   - **Overall Churn Rate:** 26.5%, indicating a substantial customer turnover rate.
   - **Gender Analysis:** Churn is nearly equal across genders, with 50.24% of churned customers being female and 49.76% male.
   - **Senior Citizens:** 25% of the churned customers are senior citizens, a notable proportion compared to other demographics.
   - **Dependents:** Only 17% of churned customers have dependents, suggesting lower attrition rates for customers with family responsibilities.

2. **Service Usage Patterns:**
   - **Internet Services:** Customers using fiber optic internet have a significantly higher churn rate (41.9%) compared to DSL (19%) and customers without internet services (7.4%).
   - **Streaming Services:** High churn is also observed among customers who subscribe to streaming TV (44%) and streaming movies (44%), indicating potential dissatisfaction with these add-on services.

3. **Billing and Payment Patterns:**
   - **Payment Method:** Electronic check users exhibit the highest churn rate at 45.3%, followed by mailed check (19.1%), bank transfer (16.7%), and credit card (15.2%).
   - **Paperless Billing:** Customers on paperless billing have a higher churn rate, with 74.91% of churned customers opting for paperless billing.
   - **Monthly Charges:** The average monthly charge for churned customers is $74, indicating a potential correlation between higher monthly costs and churn behavior.

4. **Subscription Contracts and Tenure:**
   - **Contract Types:** Month-to-month contracts see the highest churn rate at 42.7%, with significant drops for one-year (11.3%) and two-year contracts (2.8%).
   - **Tenure Analysis:** Customers with less than one year of tenure show the highest churn, at 47.4%. The churn rate decreases with tenure, indicating that long-term customers are less likely to leave.

5. **Customer Support Metrics:**
   - **Tech and Admin Tickets:** A higher volume of tech support tickets (2,955) compared to admin tickets (3,632) correlates with higher churn rates, highlighting the importance of technical service quality.

## Visuals Summary

- **Churn by Gender, Age, and Family Status**: Gender distribution of churn shows near equality, with higher churn rates among senior citizens and customers without dependents.
- **Service Usage & Churn**: High churn is associated with fiber optic internet and streaming services.
- **Payment and Billing**: The electronic check method has the highest churn rate, indicating a possible area for intervention.
- **Contract Tenure**: Shorter contract terms and lower tenure correlate with higher churn, suggesting that incentives for longer-term contracts could reduce churn.

## Recommendations from Report

1. **Incentivize Longer Contracts**: Offering incentives for yearly or bi-yearly subscriptions may help retain customers, as month-to-month contracts have the highest churn.
2. **Targeted Support for Senior Citizens**: Provide additional support and engagement strategies for senior citizens, a demographic with a high churn risk.
3. **Optimize Billing Options**: Shift electronic check users to more stable payment options, such as bank transfer or credit card, to reduce churn.
4. **Improve Service Quality for High-Risk Services**: Enhancing fiber optic and streaming service reliability and satisfaction could retain customers prone to churn.

---

