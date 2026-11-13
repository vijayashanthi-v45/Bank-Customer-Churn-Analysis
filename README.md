# **Project Type:** Internship Project – GROWAI
# Bank Customer Churn Analysis — Excel

## Project Overview

Which bank customers were more likely to leave, and which customer groups should the business examine more closely?

This project analyzes **500 customer records** to compare churn across customer characteristics and identify patterns that could inform further retention analysis.

Completed as part of a **GROWAI Data Analyst internship**, the project uses Excel formulas and PivotTables to answer 13 questions provided in the assignment, followed by 3 additional analyses.

## Business Problem

The bank needed to understand customer churn and identify groups with higher churn rates.

The analysis focused on geography, age, product count, activity status, credit score, tenure, balance, salary, and credit-card ownership.

## Project Objectives

- Measure overall customer churn.
- Compare churn rates across customer groups.
- Answer the 13 questions provided in the internship assignment.
- Conduct 3 additional analyses of churn by activity status, geography, and age group.
- Summarize findings and recommend areas for further investigation.

## My Role

As a GROWAI Data Analyst intern, I cleaned and analyzed the customer data in Excel, answered the assigned questions, and added 3 further analyses to compare churn across customer groups.

## Tools & Technologies

| Tool | Purpose |
|---|---|
| Microsoft Excel | Data cleaning and analysis |
| PivotTables | Summarizing and comparing customer groups |
| Excel formulas | Calculating customer metrics and answering assignment questions |

## Analysis Workflow

1. **Data Understanding:** Examined 500 customer records and 13 original columns.
2. **Data Cleaning:** Checked for missing values, duplicate records, and inconsistent entries.
3. **Data Preparation:** Filled 3 missing `EstimatedSalary` values using the dataset mean and excluded one inconsistent `Balance` value from the average-balance calculation.
4. **Assignment Analysis:** Used Excel formulas and PivotTables to answer the 13 questions provided in the internship assignment.
5. **Additional Analysis:** Added comparisons of churn by activity status, geography, and age group.
6. **Insight Summary:** Added short insight notes to the relevant analysis sheets.

## Key Findings

| Customer Segment | Churn Rate |
|---|---:|
| France | **59.65%** |
| Customers aged 40–49 | **57.53%** |
| Customers with 1 product | **55.20%** |
| Customers with 2 products | **54.81%** |
| Customers with 3 products | **55.08%** |
| Customers with 4 products | **52.46%** |

**Overall churn:** 272 customers (54.40%) had churned, while 228 (45.60%) had stayed.

**Activity status:** Churn rates were close for active customers (55.27%) and inactive customers (53.61%).

## What I Achieved

Completed the 13 assigned analysis questions and added 3 further churn comparisons. The results identified customer groups with higher observed churn rates, providing a basis for further investigation. No retention action or business outcome was measured.

## Business Recommendations

Based on the findings, the bank could:

- Review customer feedback and service experience in France, which had the highest churn rate among the three countries.
- Examine the needs of customers aged 40–49, while also considering the similarly high churn rate among customers under 30.
- Avoid using product count or activity status alone to identify churn risk, since the rates were close across these groups.
- Combine these patterns with additional customer information before choosing retention actions.

These are proposed actions, not measured improvements in customer retention.

## Challenges & Solutions

**Challenge:** Three `EstimatedSalary` values were missing, and one `Balance` entry contained the inconsistent value `XXXXXXXX`.

**Solution:** Filled the missing salary values using the dataset mean of **82,076.70**. Excluded the inconsistent balance entry from the average-balance calculation rather than treating it as a number.

## Limitations

- The dataset contains 500 customer records and may not represent the bank’s full customer base.
- The analysis identifies patterns and associations; it does not prove the causes of churn.
- The recommended actions have not been implemented or tested, so their impact is unknown.

## Future Enhancements

- Include customer feedback and service-interaction data to investigate possible reasons for churn.
- Compare churn patterns over different time periods.
- Evaluate the results of any future retention activities.
- Present the findings in an interactive dashboard if a dashboard is needed.

## Project Structure

```text
Bank-Customer-Churn-Analysis/
│
├── Bank_Customer_Churn_Analysis.xlsx
│   ├── Raw_Data
│   ├── Cleaned_Data
│   ├── PivotTable analysis sheets
│   └── Formula-based analysis sheets
│
├── README.md
├── Business_Insights.md
├── Data_Dictionary.md
└── Cleaning_Log.md
```

## How to View the Project

Open `Bank_Customer_Churn_Analysis.xlsx` in Microsoft Excel. The workbook contains the raw data, cleaned data, PivotTables, formula-based analyses, and insight notes.

## Conclusion

The analysis found higher observed churn in France and among customers aged 40–49. Churn rates were also similar across customers with 1–3 products and between active and inactive customers.

These findings provide a starting point for further investigation, rather than proof of why customers leave.