# 📊 Advanced Excel Financial Modeling & Pivot Dashboard

<p align="center">

**S&P 500 Financial Performance Analysis Using Microsoft Excel**

A Data Analytics Internship Project – Arrowstack

</p>

---

## 📌 1. Project Overview

This project focuses on analyzing financial performance data of S&P 500 companies using Microsoft Excel and Power Query.

The objective is to transform raw financial data into meaningful business insights through data cleaning, data quality validation, financial KPI calculations, company-wise performance analysis, PivotTables, PivotCharts, and an Excel dashboard.

The project demonstrates a practical end-to-end Excel analytics workflow, starting from raw data preparation and ending with a consolidated financial performance dashboard.

**Project Information**

| Attribute | Details |
|---|---|
| Project Name | Advanced Excel Financial Modeling & Pivot Dashboard |
| Internship | Arrowstack Data Analytics Internship |
| Task Number | Task 2 |
| Domain | Data Analytics |
| Tools | Microsoft Excel, Power Query |
| Dataset | S&P 500 Financial Data |
| Records | 2,012 |
| Unique Companies | 502 |
| Dataset Columns | 18 |

---

## 🎯 2. Project Objectives

The major objectives of this project are:

- Clean and transform raw financial data using Power Query.
- Identify missing values and duplicate company-date records.
- Perform data quality validation.
- Calculate important financial performance indicators.
- Analyze revenue, profitability, and operating performance.
- Compare financial performance across different companies.
- Use PivotTables to summarize financial information.
- Create PivotCharts for visual comparison.
- Build a consolidated financial performance dashboard.

---

## 🛠️ 3. Technologies and Tools Used

| Technology | Application |
|---|---|
| Microsoft Excel | Financial analysis and reporting |
| Power Query Editor | Data cleaning and transformation |
| PivotTables | Company-wise financial aggregation |
| PivotCharts | Financial performance visualization |
| Excel Formulas | KPI calculations and validation |
| Excel Formatting | Dashboard presentation |

---

## 📂 4. Dataset Description

The project uses an S&P 500 financial dataset containing company-level financial information.

### Dataset Statistics

| Description | Value |
|---|---:|
| Total Records | 2,012 |
| Unique Companies | 502 |
| Financial Columns | 18 |
| Missing Company Names | 0 |
| Missing Tickers | 0 |
| Missing Report Dates | 0 |

### Important Dataset Columns

The dataset includes the following financial attributes:

| Column | Description |
|---|---|
| Report_Date | Financial reporting date |
| Company | Company name |
| Ticker | Stock ticker symbol |
| R&D_Expense | Research and development expenses |
| Income_Before_Tax | Income before tax |
| Net_Income | Net income |
| SG&A_Expense | Selling, general and administrative expenses |
| Gross_Profit | Gross profit |
| EBIT | Earnings before interest and taxes |
| Operating_Income | Operating income |
| Interest_Expense | Interest-related expenses |
| Income_Tax_Expense | Income tax expenses |
| Total_Revenue | Total revenue |
| Total_Operating_Expenses | Total operating expenses |
| Cost_Of_Revenue | Cost associated with generating revenue |
| Total_Other_Income_Expense_Net | Other income and expenses |
| Net_Income_From_Continuing_Ops | Net income from continuing operations |
| Net_Income_Applicable_To_Common_Shares | Net income applicable to common shareholders |

---

## 🧹 5. Data Cleaning and Transformation Using Power Query

Power Query was used to prepare the dataset before performing financial analysis.

### Transformations Performed

**1. Data Import**
- Imported the financial dataset into Excel.
- Opened the dataset in Power Query Editor.
- Promoted the first row as column headers.

**2. Column Management**
- Removed unnecessary columns.
- Renamed columns where required.
- Reviewed the available financial attributes.

**3. Date Transformation**
- Identified report-date formatting issues.
- Applied locale-aware date conversion.
- Created a cleaned date column using Power Query transformations.
- Ensured report dates were interpreted consistently.

**4. Numeric Data Conversion**
- Converted financial columns into appropriate numeric data types.
- Reviewed empty values and data type consistency.
- Ensured financial fields could be used in calculations and aggregations.

**5. Data Loading**
- Loaded the transformed dataset into the Excel workbook.
- Verified that the final query contained 2,012 records.

---

## 🔍 6. Data Quality Analysis

A separate worksheet named `Data_Quality` was created to evaluate the quality and completeness of the dataset.

### Data Quality Results

| Validation Check | Result |
|---|---:|
| Total Records | 2,012 |
| Unique Companies | 502 |
| Missing Company Names | 0 |
| Missing Tickers | 0 |
| Missing Report Dates | 0 |
| Duplicate Company-Date Records | 5 |
| Missing Net Income | 0 |
| Missing Gross Profit | 0 |
| Missing Revenue | 0 |

### Key Observations

- All 2,012 records contain company names.
- All records contain ticker information.
- No missing report dates were identified in the quality summary.
- Five duplicate company-date records were identified.
- No missing values were reported for Net Income, Gross Profit, and Total Revenue in the checks performed.

The duplicate records were documented as part of the data quality assessment.

---

## 💰 7. Financial KPI Analysis

A separate worksheet named `Financial_KPIs` was created to calculate important financial performance metrics.

### Financial Performance Summary

| Financial Metric | Calculated Value |
|---|---:|
| Total Revenue | 1.31733E+13 |
| Total Net Income | 1.44187E+12 |
| Total Gross Profit | 5.16553E+12 |
| Total Operating Income | 2.05E+12 |
| Total Operating Expenses | 1.11E+13 |
| Average Revenue per Record | 6.55E+09 |
| Profitable Records | 1,811 |
| Loss-Making Records | 199 |
| Profitability Rate | 90.10% |

### Key Financial Metrics Explained

**Total Revenue**

Represents the sum of the revenue values across the records included in the analysis.

**Total Net Income**

Measures the aggregate net income across the prepared financial records.

**Total Gross Profit**

Represents the aggregate gross profit across the available records.

**Total Operating Income**

Summarizes operating income across the dataset.

**Total Operating Expenses**

Measures the aggregate operating expenses across the records.

**Average Revenue per Record**

Calculated as total revenue divided by the number of records.

**Profitable Records**

Counts records classified as profitable based on the net income calculation.

**Loss-Making Records**

Counts records classified as loss-making.

**Profitability Rate**

Calculated as:

`Profitability Rate = Profitable Records / Total Records Used in the Calculation × 100`

The resulting profitability rate is approximately 90.10%.

---

## 📈 8. Company-wise Financial Performance Analysis

A worksheet named `Company_Analysis` was created using Excel PivotTables.

The objective was to compare the financial performance of individual companies.

### Metrics Analyzed

- Total Revenue
- Operating Income
- Net Income
- Gross Profit

### PivotTable Implementation

The PivotTable uses:

- **Rows:** Company
- **Values:** Sum of Total Revenue
- **Values:** Sum of Operating Income
- **Values:** Sum of Net Income
- **Values:** Sum of Gross Profit

This structure enables company-wise financial comparisons without manually calculating each company's aggregated metrics.

### Top 10 Companies Visualization

A PivotChart was created to compare the selected Top 10 companies across four financial metrics:

1. Total Revenue
2. Operating Income
3. Net Income
4. Gross Profit

The chart provides a visual comparison of company-level financial performance.

---

## 📊 9. Financial Performance Dashboard

A dedicated worksheet named `Dashboard` was created to present the important financial indicators in one place.

### Dashboard Components

**KPI Cards**

The dashboard displays four important financial indicators:

| KPI | Purpose |
|---|---|
| Total Revenue | Overall revenue performance |
| Total Net Income | Overall net income |
| Total Gross Profit | Overall gross profit |
| Profitability Rate | Percentage of profitable records |

**Financial Performance Chart**

The dashboard includes a Top 10 Companies Financial Performance PivotChart.

The chart compares:
- Revenue
- Operating Income
- Net Income
- Gross Profit

### Dashboard Features

- Consolidated financial KPI summary.
- Company performance comparison.
- Percentage-based profitability indicator.
- PivotChart visualization.
- Structured and easy-to-understand layout.

The dashboard provides a quick overview of the financial analysis without requiring users to inspect every supporting worksheet.

---

## 📁 10. Excel Workbook Structure

The final workbook is organized into the following worksheets:

| Worksheet | Description |
|---|---|
| `Dashboard` | Consolidated financial performance dashboard |
| `Financial_KPIs` | Financial KPI calculations |
| `Company_Analysis` | Company-wise PivotTable and PivotChart |
| `Data_Quality` | Data quality and validation summary |
| `financial_data` | Cleaned financial dataset |

### Repository Structure

```text
Advanced-Excel-Financial-Modeling-Pivot-Dashboard/
│
├── README.md
│
└── Arrowstack_Task2_Advanced_Excel_Financial_Model.xlsx
```

---

## ▶️ 11. How to Run the Project

Follow these steps to explore the project:

1. Clone or download this GitHub repository.
2. Open the Excel workbook using Microsoft Excel.
3. Navigate to the `Dashboard` worksheet.
4. Review the financial KPI summary.
5. Open `Financial_KPIs` to inspect calculated metrics.
6. Open `Company_Analysis` to explore company-wise financial performance.
7. Open `Data_Quality` to review validation results.
8. Open `financial_data` to inspect the prepared dataset.

If the original source file is available and the Power Query connection is configured correctly, use **Data → Refresh All** to refresh the data and dependent PivotTables/PivotCharts.

---

## 📌 12. Key Project Outcomes

Through this project, the following outcomes were achieved:

- Successfully prepared a dataset containing 2,012 financial records.
- Analyzed financial information across 502 unique companies.
- Performed data cleaning and transformation using Power Query.
- Created a dedicated data quality report.
- Calculated key financial performance indicators.
- Built company-wise financial PivotTables.
- Created a Top 10 Companies PivotChart.
- Developed a consolidated financial performance dashboard.

---

## ⚠️ 13. Limitations and Considerations

- The analysis is based on the financial dataset supplied for the project.
- The dashboard does not represent real-time stock market information.
- Aggregated financial values combine the available company-period records and should be interpreted in the context of their reporting periods and units.
- Five duplicate company-date records were identified and documented in the data quality report.
- The Top 10 chart compares financial metrics with different numerical scales, so individual metric comparisons should be interpreted carefully.
- Results depend on the completeness and accuracy of the original dataset.

---

## 🎓 14. Skills Demonstrated

This project demonstrates practical experience in:

- Microsoft Excel
- Power Query
- Data Cleaning
- Data Transformation
- Data Quality Analysis
- Financial Data Analysis
- Financial KPI Reporting
- PivotTables
- PivotCharts
- Dashboard Development
- Business Reporting
- Data Interpretation

---

## 👨‍💻 15. Author

**Aayush Bharda**

B.Tech – Artificial Intelligence & Data Science

GitHub: [aayush45123](https://github.com/aayush45123)

Project Repository: [Advanced Excel Financial Modeling & Pivot Dashboard](https://github.com/aayush45123/Advanced-Excel-Financial-Modeling-Pivot-Dashboard)

---

## 🏢 16. Internship Details

**Organization:** Arrowstack  
**Internship Domain:** Data Analytics  
**Project:** Advanced Excel Financial Modeling & Pivot Dashboard  
**Task:** Task 2

This project was completed as part of the Arrowstack Data Analytics Internship assignment.

---

<p align="center">

**Thank you for visiting this project!**

*Turning raw financial data into structured insights using Excel.*

</p>
