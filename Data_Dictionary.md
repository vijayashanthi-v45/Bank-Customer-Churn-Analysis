# Data Dictionary — Bank Customer Churn Analysis

## Dataset Overview

The dataset contains **500 customer records** and **13 original fields**. The cleaned data also includes an `AgeGroup` field for age-based comparisons.

## Field Definitions

| Field | Description |
|---|---|
| `CustomerID` | Unique identifier assigned to each customer. |
| `Surname` | Customer surname. |
| `CreditScore` | Customer credit score. |
| `Geography` | Country associated with the customer: France, Germany, or Spain. |
| `Gender` | Customer gender as recorded in the dataset. |
| `Age` | Customer age in years. |
| `Tenure` | Number of years the customer has been with the bank. |
| `Balance` | Customer account balance. |
| `NumOfProducts` | Number of bank products held by the customer. |
| `HasCrCard` | Indicates whether the customer has a credit card: 1 = Yes, 0 = No. |
| `IsActiveMember` | Indicates whether the customer is an active member: 1 = Yes, 0 = No. |
| `EstimatedSalary` | Estimated customer salary. |
| `Churn` | Indicates whether the customer left the bank: 1 = Churned, 0 = Stayed. |
| `AgeGroup` | Derived age category used in the analysis: Under 30, 30–39, 40–49, or 50 and above. |

## Data Notes

- `AgeGroup` is a derived field; it is not one of the original 13 columns.
- `HasCrCard`, `IsActiveMember`, and `Churn` are recorded as binary indicators.
- Three missing `EstimatedSalary` values were filled using the dataset mean.
- One `Balance` value recorded as `XXXXXXXX` was excluded from the average-balance calculation.