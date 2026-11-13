# Data Cleaning Log — Bank Customer Churn Analysis

## Dataset Overview

- Source: Bank customer churn dataset provided for the GROWAI internship project
- Initial records: **500**
- Initial columns: **13**
- Duplicate records: **0**
- Missing `EstimatedSalary` values: **3**
- Inconsistent `Balance` entries: **1**

## Cleaning Steps

| Issue | Action Taken |
|---|---|
| 3 missing values in `EstimatedSalary` | Filled the missing values using the dataset mean of **82,076.70**. |
| One `Balance` value recorded as `XXXXXXXX` | Excluded the entry from the average-balance calculation. |
| Duplicate records | Checked for duplicates; none were found. |
| Age comparison | Added an `AgeGroup` field in the cleaned data for age-based analysis. |

## Why Were the Missing Salary Values Filled with the Mean?

Three `EstimatedSalary` values were missing. The dataset mean of **82,076.70** was used to fill those cells so the customer records could remain in the analysis.

## Why Was the Inconsistent Balance Excluded?

One `Balance` entry was recorded as `XXXXXXXX` rather than a numeric value. It was excluded from the average-balance calculation instead of being treated as a valid balance.

## Final Data Check

- Customer records: **500**
- Original columns: **13**
- Duplicate records found: **0**
- Missing `EstimatedSalary` values after filling: **0**
- `Balance` entries excluded from the average-balance calculation: **1**
- Average balance after excluding the inconsistent entry: **128,388.87**

## Output

The cleaned data and analysis are included in:

`Bank_Customer_Churn_Analysis.xlsx`

The workbook contains the raw data, cleaned data, PivotTable analyses, formula-based analyses, and insight notes.