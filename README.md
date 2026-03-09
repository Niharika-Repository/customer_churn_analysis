#  Customer Churn Analysis Power BI Dashboard
Customer churn analysis using SQL and Power BI. Includes ETL preprocessing, Power Query transformations, and DAX measures to build an interactive churn analytics dashboard.

## 1. Executive Summary
This project analyzes telecom customer churn to identify patterns in customer attrition.

An ETL workflow was used where raw CSV data was preprocessed using SQL and then loaded into Power BI for transformation and visualization.

Power Query was used for data transformations, and DAX measures were created to build an interactive Power BI dashboard for churn monitoring and customer segmentation.

---

## 2. Business Problem
Customer churn reduces recurring revenue and impacts long-term business growth.

The business wants to understand:
- Which customer segments are more likely to churn
- The relationship between tenure and churn
- The effect of monthly charges on churn behavior
- Service usage patterns among churned customers

The goal is to support data-driven customer retention strategies.

---

## 3. Methodology

### ETL Process

**Extract**
- Imported telecom churn dataset from CSV.

**Transform**
- Performed data preprocessing using SQL.
- Identified distinct values in categorical columns.
- Handled missing values using COALESCE.
- Standardized categorical fields and verified data types.

**Load**
- Loaded the processed dataset into Power BI.

### Power BI Transformations
Power Query was used to prepare the data model:

- Created churn indicator column
- Created monthly charge ranges for customer segmentation
- Generated age groups and tenure groups for demographic analysis
- Created sorting columns for group ordering
- Built service-level dataset using unpivot operations

### Power BI Dashboard
An interactive dashboard was developed with:

- KPI cards
- Customer churn metrics
- Age and tenure segmentation visuals
- Monthly charge analysis
- Service usage analysis

DAX measures were used to calculate key metrics such as total customers, churn count, and churn rate.

---

## 4. Skills

**Data Processing**
- SQL Data Cleaning
- ETL Workflow
- Data Transformation

**Data Visualization**
- Power BI Dashboard Development
- KPI Reporting
- Interactive Analytics
  
**Analytics**
- Customer Segmentation
- Churn Pattern Analysis
- Business Insight Generation

---

## 5. Results

The dashboard provides insights into customer churn across multiple segments.

- Customer churn distribution across age groups and tenure groups
- Churn patterns based on monthly charge ranges
- Service usage comparison between churned and retained customers
- Identification of high-risk customer segments using churn metrics

These insights help highlight customer groups that require targeted retention strategies.

---

## 6. Business Recommendations

- Promote long-term contracts to improve retention
- Focus retention campaigns on early-tenure customers
- Introduce targeted offers for high-charge customers
- Improve service experience for segments with high churn

---

## 7. Next Steps

Future improvements include:

- Implement churn prediction models
- Build customer lifetime value analysis
- Automate data pipelines
- Integrate real-time reporting

---

## Tools Used

- SQL
- Power BI
- Power Query
- DAX
- Data Visualization
- ETL Process
