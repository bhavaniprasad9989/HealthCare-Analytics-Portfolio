# Hospital Analysis – Excel

## Project Overview

This project uses Microsoft Excel to organize and analyze hospital healthcare data, identifying insights related to hospital distribution, bed capacity, patient discharges, patient visits, revenue, and operating expenses.

The project focuses on understanding hospital operations and financial performance across different geographical locations and reporting periods.

## Dataset Overview

The project uses the hospital dataset containing 4,379 records and 134 columns, representing 455 unique healthcare facilities across multiple counties and cities from 2017 to 2020.

The dataset includes details such as:

- Facility ID and Hospital Name
- County and City
- Hospital Type and Ownership
- Operating Status
- Reporting Year and Quarter
- Licensed, Available, and Staffed Beds
- Patient Discharges and Patient Days
- Outpatient Visits
- Gross Inpatient and Outpatient Revenue
- Net Patient Revenue
- Operating Expenses
- Capital Expenditure

## Data Cleaning and Preparation

The following data preparation and validation steps were performed:

- Inspected the dataset structure and column names.
- Checked for missing and NULL values.
- Identified duplicate records.
- Reviewed hospital identification and location information.
- Examined reporting years and quarterly periods.
- Organized hospital operational and financial metrics.
- Reviewed numerical fields for consistency.
- Identified important dimensions and measures for further analysis.

## Data Analysis

The dataset supports analysis of the following business areas:

### 1. Hospital Overview

- Total number of hospitals.
- Hospital distribution by county.
- Hospital distribution by city.
- Hospital operating status.
- Hospital classification and ownership.

### 2. Hospital Bed Capacity

- Total licensed beds.
- Total available beds.
- Total staffed beds.
- Unavailable bed capacity.
- Bed availability comparisons across hospitals.

### 3. Patient Statistics

- Total patient discharges.
- Medicare and Medicaid discharges.
- Total patient days.
- Outpatient visits.
- Payer-wise patient distribution.

### 4. Financial Analysis

- Gross inpatient revenue.
- Gross outpatient revenue.
- Total net patient revenue.
- Other operating revenue.
- Total operating expenses.
- Capital expenditure.

### 5. Geographical Analysis

- Hospital distribution across counties.
- Hospital distribution across cities.
- Comparison of hospital capacity by location.
- Geographical healthcare coverage.

## Tools and Technologies

- **Microsoft Excel:** Dataset inspection and data organization
- **Power Query:** Data preparation and transformation
- **SQL:** Data querying and analytical calculations
- **Tableau:** Interactive data visualization

## Project Files

| File Name | Description |
|---|---|
| [Hospital_Analysis.xlsx](Hospital_Analysis_Final_1.xlsx) | Hospital dataset containing 4,379 records and 134 columns |

## How to Use

1. Download the Excel dataset from this repository.
2. Open the workbook using Microsoft Excel.
3. Inspect the hospital dataset and its columns.
4. Review the reporting periods and hospital information.
5. Import the dataset into MySQL for SQL analysis.
6. Connect the dataset to Tableau for visualization.

## Conclusion

This Excel dataset provides a foundation for healthcare data analysis by organizing hospital operational, geographical, and financial information. It supports further analytical work using SQL and Tableau to identify meaningful healthcare business insights.
