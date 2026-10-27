# NYC_2019_Airbnb_Cleaned_Data
Mini project NYC_2019 Data

# NYC Airbnb Data Cleaning Project

## Project Overview
This mini project focuses on cleaning the NYC Airbnb Open Data dataset using Microsoft Excel Power Query. The goal is to prepare the data for analysis and visualization in Power BI.

## Dataset Information
- **Dataset:** NYC Airbnb Open Data
- **Source:** [Kaggle - NYC Airbnb Open Data](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data)
- **Original File:** `AB_NYC_2019.csv`
- **Sample Size:** 1,000 rows
- **Number of Columns:** 16

## Tools Used
- Microsoft Excel
- Power Query

## Data Cleaning Steps
The following steps were performed using Power Query:

1. Limited the dataset to 1,000 rows.
2. Replaced the missing value in `host_name` with `Unknown`.
3. Applied Capitalize Each Word formatting to the `name` column.
4. Retained null values in `last_review` and `reviews_per_month`.
5. Checked and verified column data types.
6. Checked for duplicate listing IDs. No duplicate IDs were found in the selected sample.
7. Checked column quality. No errors were reported.
8. Checked numerical columns for unusual values, including `price`, `minimum_nights`, `number_of_reviews`, and `availability_365`.
9. Reviewed text consistency in relevant columns.

## Handling Missing Values

| Column | Action Taken |
|---|---|
| `host_name` | Replaced the missing value with `Unknown` |
| `last_review` | Retained null values |
| `reviews_per_month` | Retained null values |

Null values in review-related columns were retained because missing information should not automatically be treated as zero or replaced with invented values.

## Data Validation
The selected dataset was checked for:
- Appropriate data types
- Duplicate listing IDs
- Power Query errors
- Unusual numerical values
- Text consistency

**Validation results:**
- Duplicate listing IDs: None found
- Power Query errors: None reported
- Negative prices: None found

## Project Output
The cleaned dataset is intended for further analysis and visualization in Power BI.

## Screenshots
added

## Limitations
- The project uses a 1,000-row sample rather than the complete dataset.
- Findings from this sample may not represent all NYC Airbnb listings.
- Null values were retained where replacing them could introduce inaccurate information.

## Conclusion
This project provided practical experience in data cleaning using Excel Power Query, including handling missing values, formatting text, checking data types, validating numerical values, and checking for duplicates and errors. The cleaned dataset will serve as the foundation for further analysis and visualization in Power BI.
