# Business Insights — Bank Customer Churn Analysis

## 1. Business Objective

Identify customer groups with higher churn rates, understand the observed patterns, and recommend areas for further retention analysis.

## 2. Overall Churn

- **Total customers:** 500
- **Churned:** 272 (54.40%)
- **Retained:** 228 (45.60%)

More than half of the customers in this dataset had churned.

## 3. Key Business Findings

### Geography

- **Finding:** France had the highest churn rate at **59.65%**, followed by Germany at **52.23%** and Spain at **51.16%**.
- **Business Insight:** Review customer feedback and service experience in France to investigate the higher observed churn rate.

### Age Group

- **Finding:** Customers aged 40–49 had the highest churn rate at **57.53%**. Customers under 30 were close at **56.67%**.
- **Business Insight:** Examine the needs and feedback of both groups before deciding whether to plan targeted retention activities.

### Number of Products

- **Finding:** Churn rates were **55.20%** for customers with 1 product, **54.81%** for 2 products, **55.08%** for 3 products, and **52.46%** for 4 products.
- **Business Insight:** Rates were similar across customers with 1–3 products, so product count alone does not clearly distinguish churn risk.

### Activity Status

- **Finding:** Churn was **55.27%** among active customers and **53.61%** among inactive customers.
- **Business Insight:** The rates were close, and active customers had a slightly higher observed rate. Activity status alone is not a clear indicator of churn.

### Credit Score and Tenure

- **Finding:** For customers with 1 year of tenure, average credit score was **616.83** among churned customers and **591.00** among retained customers. The averages did not show a consistent pattern across tenure groups.
- **Business Insight:** Credit score alone does not explain the churn pattern; consider it alongside other customer characteristics.

### Balance

- **Finding:** The average balance was **128,388.87**, calculated after excluding one inconsistent `Balance` entry.
- **Business Insight:** This is a descriptive value and does not establish a relationship between balance and churn.

### Credit Card Ownership

- **Finding:** **131 churned customers** had a credit card.
- **Business Insight:** Credit-card ownership did not prevent these customers from churning; it should not be used alone to assess churn risk.

### Salary

- **Finding:** The average estimated salary among churned customers was **83,428.09**.
- **Business Insight:** This is descriptive information and does not establish that salary caused churn.

## 4. Business Recommendations

1. Review customer feedback and service experience in France.
2. Examine the needs of customers aged 40–49 and under 30.
3. Avoid using product count or activity status alone to identify customers at risk of churn.
4. Consider credit score, balance, salary, and credit-card ownership alongside other customer information.
5. Gather additional customer feedback and service-interaction data before choosing retention actions.

## 5. Conclusion

The highest observed churn rates were in France and among customers aged 40–49. Churn rates were similar across customers with 1–3 products and between active and inactive customers.

These findings can guide further investigation, but they do not prove the causes of churn or demonstrate that any retention action would reduce it.

**Note:** The analysis identifies associations, not proven causes. The effectiveness of the recommendations has not been measured.