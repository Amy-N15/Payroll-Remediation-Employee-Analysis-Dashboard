# 💰 Payroll Remediation & Employee Analysis Dashboard

> A Power BI dashboard designed to analyse payroll compliance, employee compensation, overtime obligations, and workforce costs. The solution integrates 14 payroll and workforce datasets to identify potential underpayments, remediation exposure, entitlement gaps, and workforce trends across 100 employees.

---

## 📊 Dashboard Preview

| Payroll Remediation                                    |
| --------------------------------------------------- |
| <img width="911" height="513" alt="image" src="https://github.com/user-attachments/assets/4f7cc597-bb6a-44eb-8e3f-5ea19efae4f2" />|

| Employee Analysis                                              |
| -------------------------------------------------------------- |
| <img width="913" height="509" alt="image" src="https://github.com/user-attachments/assets/d231a713-6c0a-484b-9991-3604b507289e" />

---

## 🎯 Business Problem

Payroll remediation has become a significant compliance challenge for organisations. Errors in minimum wage calculations, overtime payments, casual loadings, penalty rates, leave entitlements, and junior pay rates can result in underpayments, financial penalties, and reputational damage.

This dashboard was developed to:

* Monitor payroll compliance and workforce costs
* Identify potential underpayment risks
* Compare employee pay against minimum wage requirements
* Analyse overtime and penalty rate exposure
* Support payroll remediation and workforce planning decisions

---

## 📈 Key Metrics at a Glance

| Metric                | Value              |
| --------------------- | ------------------ |
| Total Employees       | 100                |
| Active Employees      | 75                 |
| Inactive Employees    | 25                 |
| Contracts             | 105                |
| Timesheet Records     | 45,607             |
| Total Hours Logged    | 253,868.8          |
| Total Bonuses Paid    | $920,471.89        |
| Total Allowances Paid | $26,452.70         |
| Leave Records         | 378                |
| Pay Rate Range        | $20.08 – $49.87/hr |

---

## 🧠 Skills Demonstrated

* Data Modelling (Star Schema)
* Power Query Data Transformation
* DAX Calculations
* Payroll Compliance Analysis
* Workforce Analytics
* Data Visualisation
* KPI Development
* Business Reporting
* Data Validation & Quality Checks

---

## 🔍 Dashboard Features

### Workforce Overview

* Employee demographics and workforce composition
* Active vs inactive employee analysis
* Gender and location breakdowns
* Workforce distribution by role

### Contract Analysis

* Permanent, Casual, and Fixed-Term employment analysis
* Employment type distribution
* Pay frequency tracking
* Contract status monitoring

### Payroll Remediation

* Pay rate comparison against minimum wage requirements
* Junior pay rate compliance checks
* Casual loading validation
* Underpayment risk identification

### Timesheets & Overtime

* Worked hours analysis
* Overtime tracking
* Sunday penalty calculations
* Night shift allowance monitoring

### Compensation Analysis

* Bonus payment trends
* Allowance distribution
* Employee compensation overview
* Cost monitoring

### Leave Management

* Annual leave analysis
* Sick leave tracking
* Unpaid leave monitoring
* Leave liability insights

---

## 📌 Key Insights

### Workforce Structure

* Only 41% of contracts are permanent, while 59% are Casual or Fixed-Term arrangements.
* A high proportion of non-permanent contracts increases payroll complexity due to varying entitlement calculations and compliance requirements.

### Payroll Compliance Exposure

* Employee pay rates range from $20.08 to $49.87 per hour.
* Employees near the lower end of the pay scale should be prioritised for remediation reviews following annual minimum wage increases.

### Overtime & Penalty Risks

* Payroll calculations incorporate six different penalty and loading rules including overtime, Sunday penalties, night shift allowances, and casual loading.
* The complexity of these calculations increases the likelihood of payroll errors and highlights the importance of automated validation checks.

### Compensation Trends

* More than $920,000 was paid through bonus programs.
* Performance bonuses account for approximately 69% of all bonus transactions, indicating a strong focus on incentive-based compensation.

### Leave Liability

* Employees accumulated over 2,000 leave hours across 378 leave records.
* Annual leave represents the largest leave category and should be monitored to manage future leave liabilities.

---

## 📊 Project Outcomes

* Integrated 14 payroll and workforce datasets into a unified reporting model
* Built DAX measures to support payroll compliance and remediation analysis
* Developed interactive dashboards for workforce, compensation, overtime, and leave analysis
* Enabled drill-through reporting from organisation-level KPIs to individual employee records
* Applied payroll business rules including casual loading, penalty rates, overtime multipliers, and junior pay rate calculations

---

## 🗂️ Repository Structure

```text
payroll-remediation-dashboard/
│
├── datasets/
│   ├── employee_details.csv
│   ├── contract_details.csv
│   ├── timesheet.csv
│   ├── roster.csv
│   ├── allowance.csv
│   ├── bonus.csv
│   ├── employee_leave.csv
│   ├── time_off_in_lieu.csv
│   ├── minimum_pay_rates.csv
│   ├── junior_pay_rates.csv
│   ├── pay_rate_adjustments.csv
│   ├── tax_rates.csv
│   ├── combined_holidays.csv
│   └── dim_dates.csv
│
├── assets/
│   └── screenshots/
│
├── docs/
│   └── insights_summary.md
│
├── Payroll_Remediation___Employee_Analysis_Dashboard.pbix
├── README.md

```

---

## 🛠️ Tools & Technologies

* Power BI Desktop
* Power Query
* DAX
* CSV Data Sources
* Data Modelling
* Star Schema Design

---

## ⚙️ Getting Started

### Prerequisites

* Power BI Desktop

### Installation

```bash
git clone https://github.com/Amy-N15/Payroll-Remediation-Employee-Analysis-Dashboard.git
```

### Open the Report

1. Launch Power BI Desktop
2. Open the `.pbix` file
3. Refresh data connections if required
4. Explore dashboard insights using slicers and filters

---

## 🚀 Future Enhancements

* Payroll forecasting and cost projections
* Automated underpayment detection alerts
* Workforce turnover analysis
* Leave liability forecasting
* Award interpretation and compliance monitoring

---

## 🤝 Acknowledgements

Built as part of a Data Analytics portfolio project.

Payroll compliance logic is based on Australian minimum wage schedules, casual loading requirements, overtime provisions, and employee entitlement frameworks.

---

## 📄 Licence

This project is provided for portfolio and educational purposes only.

All employee information has been anonymised.
