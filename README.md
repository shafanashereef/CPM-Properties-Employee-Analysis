# CPM Properties Workforce Analysis Dashboard

## Project Overview
This project was developed as part of a **Data Analyst Internship at Data GUC** in collaboration with **CPM Properties**, a real estate company operating across the UAE.

The objective of this project is to analyze workforce data and build an **interactive Power BI dashboard** that provides insights into employee performance, development, retention risk, and demographic factors.

The dashboard enables stakeholders to understand workforce trends better and evaluate whether promotion decisions align with defined eligibility criteria.

---

# About CPM Properties
**Conrad Property Management (CPM)** is a leading real estate agency in the UAE specializing in property sales and leasing.

The company has successfully served **4,500+ customers** and operates with a team of **100+ professional agents** across multiple locations. CPM offers residential, commercial, and retail property solutions while providing comprehensive leasing and property management services.

---

# Project Objectives
The main objectives of this analysis are to examine key workforce dimensions, including:

- **Employee Performance Indicators**
- **Development and Engagement Factors**
- **Employee Retention & Attrition Risk**
- **Demographic & Contextual Factors**

Additionally, the dashboard answers two important workforce questions:

- Did **eligible candidates receive promotions?**
- Did **ineligible candidates receive promotions?**

---

# Dataset Description
The dataset contains **200 employees** with multiple attributes related to performance, engagement, and demographics.

### Key Columns
- Employee ID
- Employee Name
- Age
- Gender
- Department
- Post
- Education
- Nationality
- Region
- Salary Band
- Length of Service
- KPI Score
- Engagement Score
- Training Score
- Previous Year Rating
- Productivity Index
- Absenteeism Rate
- Attrition Risk Score
- Number of Trainings
- Awards Won
- Recruitment Channel
- Promotion Status

---

# Data Preparation
Before building the dashboard, the dataset was prepared to ensure data quality and consistency.

Steps performed:

- Verified **no missing values**
- Checked **duplicate records**
- Standardized categorical fields
- Validated data ranges for performance metrics
- Created calculated columns and measures in Power BI

### Calculated Columns
- **Promotion Eligibility**
- **Risk Category**
- **Promotion Status**

### Key Measures
- Total Employees
- Total Promoted
- Promotion Rate
- Average KPI Score
- Average Engagement Score
- Average Productivity
- Average Attrition Risk
- Eligible Promotion Rate
- Ineligible Promotion Rate

---

# Dashboard Structure

The Power BI dashboard contains **two main analysis pages**:

### Workforce Performance & Development
Focuses on employee performance and development indicators.

Key metrics analyzed:
- KPI performance
- Productivity
- Training impact
- Engagement levels
- Department-level performance

### Retention Risk & Promotion Insights
Focuses on workforce risk, demographics, and promotion analysis.

Key metrics analyzed:
- Attrition risk categories
- Promotion eligibility vs actual promotions
- Department-level promotion distribution
- Demographic factors affecting promotions

Interactive **slicers** allow filtering by:
- Department
- Region
- Gender
- Education

---

# Key Insights

### Employee Performance
- Overall promotion rate is **24%**.
- KPI scores are generally high across departments.
- High performance does not always guarantee promotion.

### Development & Engagement
- Promoted employees tend to have slightly higher training scores.
- Some non-promoted employees show strong engagement levels.

### Retention Risk
- The majority of employees fall under **Low Risk** category.
- Some **High Risk employees were still promoted**, which may affect retention planning.

### Demographic Factors
- Promotion rates are relatively balanced across genders.
- Education level appears to influence promotion more than nationality.

### Promotion Eligibility
- Some eligible employees were promoted.
- However, **several ineligible employees also received promotions**, indicating possible gaps in promotion criteria alignment.

---

# Recommendations

- Improve alignment between **promotion criteria and promotion decisions**.
- Establish **standardized promotion evaluation frameworks**.
- Monitor **high-performing employees who are not promoted** to prevent disengagement.
- Implement targeted **retention strategies for high-risk departments**.
- Integrate **attrition risk analysis into workforce planning**.
- Continue monitoring promotion trends across departments and demographics.

---

# Tools & Technologies

- **Power BI**
- **DAX (Data Analysis Expressions)**
- **Data Cleaning & Transformation**
- **Interactive Dashboard Design**
- **Workforce Analytics**
