📊 Telecom Customer Churn Analysis and retention strategy

## Business Analysis | SQL | Power BI | Python | Machine Learning | Excel

## Project Overview
This end-to-end Business Analysis project examines customer churn in a telecom company using a dataset of 6,418 customers. The objective was to identify key churn drivers, quantify revenue impact, segment customers based on risk, and recommend business strategies to improve customer retention.

| Detail            | Information                                  |
| ----------------- | -------------------------------------------- |
| Project Type      | End-to-End Business Analysis                 |
| Dataset Size      | 6,418 Customers                              |
| Tools Used        | SQL, Python, Power BI, Excel                 |
| Focus Area        | Customer Churn Analysis & Retention Strategy |
| Churn Rate        | 26.99%                                       |
| Customers Churned | 1,732                                        |
| Revenue at Risk   | $3,411,960                                   |

## Business Problem
The company experienced a customer churn rate of 26.99%, resulting in significant customer and revenue loss.
The objectives of this project were to:
* Identify the primary reasons customers leave
* Segment customers by churn risk
* Measure the financial impact of churn
* Develop data-driven retention strategies
* Estimate potential revenue recovery opportunities

## Key Findings
| Metric                            | Result                  |
| --------------------------------- | ----------------------- |
| Customers Churned                 | 1,732 (26.99%)          |
| Primary Churn Driver              | Competitor Offers (44%) |
| Month-to-Month Churn Rate         | 46.5%                   |
| Two-Year Contract Churn Rate      | 2.7%                    |
| Fiber Optic Churn Rate            | 41.1%                   |
| Revenue Lost from Fiber Customers | $2,782,240              |
| High-Risk Customer Segment        | 625 Customers           |
| High-Risk Segment Churn Rate      | 60.3%                   |

## Business Recommendations

### 1. Stay & Save Contract Program

**Target Group:** Month-to-Month Customers
**Recommendation:**
Offer contract upgrade incentives and discounts to encourage migration to annual plans before customers begin evaluating competitors.
**Expected Outcome:**
Reduction in churn among month-to-month customers and increased customer retention.

### 2. Competitive Loyalty Program
**Target Group:** Customers at Risk of Switching to Competitors
**Recommendation:**
Introduce loyalty rewards, retention offers, and personalized pricing benefits at key customer milestones.
**Expected Outcome:**
Improved customer loyalty and reduced competitor-driven churn.

### 3. Fiber Optic Success Program
**Target Group:** Fiber Optic Customers
**Recommendation:**
Implement proactive customer engagement through onboarding calls, satisfaction surveys, and support follow-ups.
**Expected Outcome:**
Improved customer satisfaction and lower churn rates within the highest-risk service segment.

## Revenue Recovery Scenarios

| Retention Improvement | Estimated Revenue Recovered |
| --------------------- | --------------------------- |
| 10% Improvement       | $341,196                    |
| 20% Improvement       | $682,392                    |
| 30% Improvement       | $1,023,588                  |

## Power BI Dashboard

The dashboard consists of five analytical pages:

### Executive Summary
* Overall KPIs
* Customer distribution
* Churn overview

### Churn Analysis
* Churn by demographics
* Churn by services
* Churn by contract type

### Churn Drivers
* Reasons for customer attrition
* Competitor impact analysis

### Revenue Impact
* Revenue loss analysis
* Recovery scenario modeling
* Business KPI tracking

### Customer Risk Segmentation
* High Risk Customers
* Medium Risk Customers
* Low Risk Customers
* Recommended actions

## Machine Learning Analysis
The Python workflow included:
* Data Cleaning and Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Churn Prediction Model
* Feature Importance Analysis

Libraries Used:
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn

## Customer Risk Segmentation

| Segment     | Criteria                                                  | Customers | Churn Rate |
| ----------- | --------------------------------------------------------- | --------- | ---------- |
| High Risk   | Month-to-Month + Fiber Optic + Less than 12 Months Tenure | 625       | 60.3%      |
| Medium Risk | Month-to-Month Customers                                  | 2,661     | 43.3%      |
| Low Risk    | Annual and Two-Year Contract Customers                    | 3,132     | 6.5%       |

## Project Structure

``text
telecom-churn-analysis/

├── data/
│   └── Customer_Data.csv

├── sql/
│   └──data exploration.sql

├── notebooks/
│   └── churn_prediction.ipynb

├── powerbi/
│   └── Churn_Analysis.pbix

├── documents/
│   ├── Executive_Summary.pdf
│   └── Business_Recommendations.docx
│   └──Churn_Analysis_BA_Presentation.pptx

├── screenshots/
│   ├── Executive_Summary.png
│   ├── Churn_prediction.png
│   ├── Revenue_Impact.png
│   └── Risk_Segmentation.png

└── README.md
``

## Tools & Technologies
* SQL
* Python
* Power BI
* Excel
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib

## Author

**Devanshi Singh**

Aspiring Business Analyst | Data Analyst

Skills: SQL • Python • Power BI • Excel • Data Analytics • Business Analytics

LinkedIn: [www.linkedin.com/in/devanshisingh-analyst]

GitHub: [Devanshisingh123]


This project demonstrates the application of business analysis, data analytics, machine learning, and dashboard development to identify customer churn drivers and recommend actionable retention strategies with measurable business impact.
