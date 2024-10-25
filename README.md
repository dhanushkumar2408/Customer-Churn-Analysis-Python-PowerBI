# Customer-Churn-Analysis

**TOOLS USED**:  Python , PowerBI



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

#### **Recommended Actions**:
1. **Target High-Risk Segments**:
   - Focus retention strategies on customers with short tenures, particularly those in their first year of service. Offering discounts or service upgrades could reduce churn.
2. **Offer Incentives for Contract Upgrades**:
   - Encourage month-to-month customers to switch to longer-term contracts by offering promotions or loyalty programs. Customers on longer-term contracts have a churn rate of less than **5%**.
3. **Review Pricing for High Monthly Charge Customers**:
   - Consider restructuring pricing for high-spending customers. With over **45%** churn among customers paying more than \$80/month, offering bundled discounts or loyalty bonuses could improve retention.
4. **Promote Automatic Payment Methods**:
   - Since customers using electronic checks have a much higher churn rate (**46%**), promoting automatic bank or card payments may lower churn by ensuring timely payments.
