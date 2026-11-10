
# Fraud & AML Risk Analysis | Excel Portfolio Project

An Excel-based financial crime analytics project focused on suspicious transaction identification, customer risk assessment, KYC indicators, AML alert analysis, and case management.

---

## 📌 Project Overview

This project analyzes financial transaction data to identify suspicious activity patterns, assess customer risk indicators, examine AML alert outcomes, and understand case-management results.

The analysis was performed entirely using Microsoft Excel, applying data cleaning, data validation, PivotTables, calculated metrics, and data visualization techniques.

## 🎯 Project Objectives

- Analyze financial transaction patterns and suspicious activity indicators.
- Identify transaction channels with higher suspicious activity rates.
- Evaluate customer risk scores and KYC classifications.
- Examine AML alert outcomes and detection-rule categories.
- Analyze case dispositions and SAR filing outcomes.
- Translate analytical findings into meaningful financial crime insights.

## 🗂️ Dataset Information

| Dataset Component | Records |
|---|---:|
| Transactions | 42,203 |
| Customers | 300 |
| Accounts | 487 |
| Counterparties | 1,500 |
| Alerts | 84 |
| Cases | 38 |

- **Dataset Title:** AML Transaction Monitoring
- **Source:** Misata Studio
- **Tables Used:** 6
- **Primary Tool:** Microsoft Excel

## 🛠️ Tools & Methodology

**Microsoft Excel**

- Data Cleaning and Validation
- Duplicate and Missing Value Checks
- Excel PivotTables
- Excel Formulas and Calculated Metrics
- Conditional Formatting
- Transaction and Customer Segmentation
- Data Visualization
- Analytical Reporting

## 📊 Analysis & Key Findings

### 1. Transaction Analysis

Analyzed 42,203 financial transactions to examine transaction volumes, amounts, suspicious indicators, and overall activity patterns.

| Metric | Result |
|---|---:|
| Total Transactions | 42,203 |
| Suspicious Transactions | 726 |
| Non-Suspicious Transactions | 41,477 |
| Suspicious Transaction Rate | 1.72% |
| Total Transaction Amount | $30,126,065.20 |
| Suspicious Transaction Amount | $5,001,168.54 |
| Suspicious Amount Share | 16.60% |

**Key Insight:** Although suspicious transactions represented only 1.72% of total transactions, they accounted for 16.60% of the total transaction value.

### 2. Transaction Channel Analysis

Examined suspicious transaction rates across different transaction channels.

| Transaction Channel | Suspicious Rate |
|---|---:|
| Branch | 23.15% |
| Online | 1.21% |
| ATM | 1.12% |
| Wire | 0.46% |
| Card | 0.00% |
| Mobile | 0.00% |

**Key Insight:** Branch transactions recorded the highest observed suspicious transaction rate (23.15%) among the analyzed channels, indicating a concentration of suspicious indicators in branch-based activity.

### 3. Customer Risk Assessment

Analyzed customer risk scores and suspicious activity indicators across different risk-score ranges.

| Risk Score | Customers | Suspicious Customers | Suspicious Rate |
|---|---:|---:|---:|
| 1–20 | 70 | 1 | 1.43% |
| 21–40 | 152 | 8 | 5.26% |
| 41–60 | 71 | 5 | 7.04% |
| 61–80 | 7 | 1 | 14.29% |
| **Total** | **300** | **15** | **5.00%** |

**Key Insight:** Suspicious customer rates increased across the analyzed risk-score bands. However, the highest risk band contained only seven customers, so the result should be interpreted cautiously.

### 4. KYC Risk Analysis

Examined customer KYC classifications and their relationship with suspicious activity indicators.

| KYC Rating | Customers | Suspicious Customers | Suspicious Rate |
|---|---:|---:|---:|
| High | 4 | 0 | 0.00% |
| Medium | 94 | 9 | 9.57% |
| Low | 202 | 6 | 2.97% |
| **Total** | **300** | **15** | **5.00%** |

**Key Insight:** Suspicious activity indicators were observed across different KYC classifications. Medium-rated customers accounted for the highest number of suspicious customers, highlighting the importance of ongoing transaction monitoring.

### 5. AML Alert Outcome Analysis

Reviewed 84 AML alerts to examine alert outcomes and detection-rule categories.

**Alert Outcomes**

| Alert Outcome | Count |
|---|---:|
| True Positive | 50 |
| False Positive | 34 |
| **Total Alerts** | **84** |

**Detection Rule Analysis**

| Detection Rule | Alerts |
|---|---:|
| Profile Deviation | 59 |
| Rapid In/Out | 12 |
| High-Risk Geography | 10 |
| Cash Near Threshold | 3 |
| **Total** | **84** |

**Key Insight:** Profile Deviation generated the highest alert volume, accounting for 59 of the 84 alerts. The dataset recorded 50 true-positive outcomes, representing approximately 59.52% of all reviewed alerts.

### 6. Case Management & SAR Analysis

Examined case outcomes, associated alerts, and Suspicious Activity Report (SAR) filing patterns.

| Case Outcome | Number of Cases |
|---|---:|
| SAR Filed | 19 |
| Closed No Action | 19 |
| **Total Cases** | **38** |

**Key Findings:**

- 38 cases were reviewed.
- 19 cases resulted in SAR filing.
- 19 cases were closed with no action.
- 84 alerts were associated with the reviewed cases.

**Key Insight:** Case outcomes were evenly distributed between SAR filing and closure with no action, providing an overview of the investigation and case-disposition patterns in the dataset.

## 📈 Key Project Insights

- Suspicious transactions represented 1.72% of total transaction volume but accounted for 16.60% of total transaction value.
- Branch transactions recorded the highest suspicious activity rate at 23.15%.
- Suspicious customer rates increased across the analyzed risk-score bands.
- Profile Deviation was the most frequent AML alert detection rule.
- 50 of 84 alerts were classified as true positives in the dataset.
- Case outcomes were evenly distributed between SAR filing and closure with no action.

## 📁 Repository Structure

```text
Fraud-AML-Risk-Analysis/
│
├── README.md
│
├── Analysis/
│   └── Fraud_AML_Analysis.xlsx
│
├── Report/
│   └── Fraud_AML_Analysis_Report.pdf
│
└── Visualizations/
    ├── Transaction_Analysis.png
    ├── Customer_Risk_Analysis.png
    ├── Alert_Analysis.png
    └── Case_Analysis.png
```

## 💡 Skills Demonstrated

**Technical Skills**
- Microsoft Excel
- Data Cleaning and Validation
- PivotTable Analysis
- Excel Formulas and Calculated Metrics
- Data Visualization
- Analytical Reporting

**Financial Crime Domain Knowledge**
- Fraud Analysis
- Financial Transaction Monitoring
- Customer Risk Assessment
- KYC Fundamentals
- AML Alert Analysis
- Case Management
- SAR Filing Concepts

## ⚠️ Project Limitations

- This is an independent portfolio project using a provided dataset.
- The analysis is descriptive and based on existing dataset indicators and labels.
- Suspicious indicators do not independently establish financial crime.
- No machine-learning model or automated fraud detection system was developed.
- Dataset redistribution is subject to the original source's licensing and permissions.

## 👩‍💻 About Me

**Aspiring Data Analyst | Financial Crime & Fraud Analytics**

Interested in applying data analytics to financial services, fraud analysis, and financial crime risk operations.

**Technical Skills:** Excel, SQL, Python, Power BI

**Additional Domain Knowledge:** Fraud Analysis, KYC, AML and Financial Crime Fundamentals.

---

⭐ Thank you for exploring my project!
