# Student-Loan-Debt-MLR

Predicting total student-loan debt at graduation from socioeconomic and institutional factors with multiple linear regression models.

---

## Course  
**ISYE 6414: Regression Analysis**

## Members  
- Aashna Manoj Punwani
- Vinoj Zachariah
- Hoang Nguyen  
- Eric Simmons
- Mohammed Saif Qureshi

---

## Background

College costs have risen faster than inflation for decades, pushing U.S. students to borrow heavily, but debt burdens are uneven.  
This project quantifies which factors (family income, tuition, aid, major, school type, employment, residency status) most strongly influence how much a student owes at graduation.

---

## Research Questions

1. Which socioeconomic and academic factors significantly predict total loan balance?  
2. Does holding a job while in college reduce borrowing?  
3. Do in-state and out-of-state students differ in debt levels?

---

## Data Sources

| Dataset              | Purpose                                           |
|----------------------|---------------------------------------------------|
| **NPSAS**            | Core micro-level borrowing and demographics       |
| **IPEDS**            | Tuition and fee data                              |
| **College Scorecard**| Program-level earnings and institution controls   |
| **U.S. Census / ACS**| Regional SES and cost-of-living context           |

---

## Project Structure

```text
student-loan-debt-mlr/
│
├── README.md          <- project overview (this file)
├── requirements.txt   <- Python dependencies
│
├── data/              <- raw CSV/SAS extracts (git-ignored)
├── preprocess/        <- cleaning and merge scripts/notebooks
├── eda/               <- exploratory notebooks and plots
└── model/             <- regression notebooks and diagnostics
