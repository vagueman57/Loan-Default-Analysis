# 🏦 Loan Default Analysis | Power BI

An end-to-end **Loan Default Analysis Dashboard** built using Power BI and Microsoft SQL Server to analyze lending patterns, applicant demographics, financial profiles, and loan default risks. The project integrates data connectivity, secure refresh, and reporting through Power BI Gateway and Power BI Service.

## 📊 Dashboard Preview

### 1. Loan Default Overview

Analyzes loan distribution and default patterns across different applicant segments.

![Loan Default Overview](<Screenshot 2026-10-18 000745.png>)

- Loan Amount by Purpose
- Average Income by Employment Type
- Default Rate by Employment Type
- Average Loan Amount by Age Group
- Default Rate by Year

### 2. Applicant Demographics & Financial Profile

Explores how credit scores, income, education, and applicant characteristics relate to borrowing behavior.

![Applicant Demographics and Financial Profile](<Screenshot 2026-10-18 000808.png>)

- Median Income and Loan Amount by Credit Score Bins
- Average Loan Amount for High Credit Score Applicants
- Total Loan Amount by Credit Score Category
- Loan Analysis of Middle-Aged Applicants with Mortgages and Dependents
- Total Number of Loans by Education Type

### 3. Financial Trends & Loan Portfolio Analysis

Tracks year-over-year changes and examines the composition of the loan portfolio.

![Financial Trends and Loan Portfolio Analysis](<Screenshot 2026-10-18 000824.png>)

- Year-over-Year (YoY) Loan Amount Change
- Year-over-Year (YoY) Default Loan Change
- Year-to-Date (YTD) Loan Amount by Credit Score Bins and Marital Status
- Loan Amount Breakdown by Income Bracket and Employment Type

## 🛠️ Tech Stack

- **Power BI Desktop:** Interactive dashboards and data visualization
- **Microsoft SQL Server:** Data storage and querying
- **Power BI Gateway:** Connectivity between the on-premises data source and Power BI Service
- **Power BI Service:** Report publishing and refresh management

## 🔄 End-to-End Data Workflow

1. **Data Storage:** Loan data is maintained in Microsoft SQL Server.
2. **Data Connectivity:** Power BI connects to SQL Server using the configured connection mode.
3. **Gateway Integration:** The on-premises data gateway enables secure communication with Power BI Service.
4. **Refresh & Reporting:** Configured refresh or supported live-query functionality keeps reports updated according to the connection mode.
5. **Visualization:** Interactive dashboards enable analysis of lending trends, applicant profiles, and default risks.

This architecture supports secure access to on-premises data without requiring the underlying database to be migrated to the cloud.

## 🎯 Project Objectives

- Identify loan default patterns across employment types and age groups.
- Analyze the relationship between credit scores, income, and loan amounts.
- Track yearly changes in lending and defaults.
- Explore applicant demographics and loan portfolio composition.
- Implement an end-to-end business intelligence workflow.

## 💡 Skills Demonstrated

**Power BI · SQL Server · Data Visualization · Power BI Gateway · Power BI Service · Business Intelligence · Financial Data Analysis**

---
