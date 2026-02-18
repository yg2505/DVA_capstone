# 📊 Loan Risk & Repayment Analysis Dashboard  
### A Data-Driven Study on Loan Size, Interest Bands & Default Risk  

---

## 🏦 Sector  
**Banking & Financial Services – Consumer Unsecured Lending**

---

## 👥 Team Members  

- Yashvi Goyal  
- Shreya Narayani  
- Trishit Swarnakar  
- Dev Kothari  
- Anshvardhan Badkur  
- Vansh Jain  
- Nikith Gowda BS  

---

## 📌 Project Overview  

Financial institutions often struggle to clearly connect loan characteristics (loan size, interest rate band, borrower financial stress indicators) with repayment outcomes.

Weak segmentation leads to:
- Higher default rates  
- Inefficient capital allocation  
- Reduced portfolio profitability  

This project analyzes **49,999 consumer loans** and builds an interactive **Google Sheets Risk Dashboard** to identify structured default patterns across:

- Loan Size (Amount Band)  
- Interest Rate Band  
- Loan Status Distribution  
- Default Concentration Trends  

---

## 🎯 Business Objective  

To build a structured KPI-driven framework that helps lenders:

- Identify high-risk segments  
- Monitor portfolio default concentration  
- Improve risk-based approval strategies  
- Support smarter credit allocation decisions  

---

## 📂 Dataset  

- **Source:** GitHub (Lending Dataset)  
- **Records:** 49,999 loans  
- **Variables:** ~30 borrower & loan attributes  
- **Loan Type:** Consumer unsecured lending  

---

## 🧹 Data Preparation (Google Sheets)

### Cleaning Steps
- Converted interest rate from text to numeric format  
- Standardized categorical fields  
- Removed inconsistencies in loan status  
- Handled missing values  
- Created structured segmentation bands  

### Engineered Features
- **Interest Rate Band:** Low, Medium, High, Very High  
- **Loan Amount Band:** Low, Medium, High, Very High  
- Loan Status Categories:
  - Fully Paid  
  - Current  
  - Charged Off (treated as Default)  

### Assumptions
- Charged Off = Default  
- Fully Paid = Successful repayment  
- Current loans considered active (non-defaulted)  

---

## 📊 KPI Framework  

| KPI | Value | Business Meaning |
|------|--------|------------------|
| Total Loans | 49,999 | Portfolio size |
| Total Defaults | 7,579 | Risk exposure |
| Fully Paid Loans | 27,074 | Successful repayments |
| Overall Default Rate | 15.16% | Core risk indicator |

These KPIs form the executive layer of the dashboard.

---

## 📊 Dashboard Structure  

### 🔹 Executive Overview
Displays:
- Total Loans  
- Fully Paid  
- Total Defaults  
- Overall Default Rate  

Interactive Filters:
- Interest Rate Band  
- Loan Amount Band  

---

### 🔹 Loan Size Analysis

**1️⃣ Loan Status Distribution by Loan Size**  
Stacked bar chart showing:
- Fully Paid  
- Current  
- Charged Off  

**2️⃣ Default Rate by Loan Size**  
Default increases as loan size increases.  
Very High loan size shows the highest default percentage.

**3️⃣ Charged-Off Loans Trend by Loan Size**  
Trend line highlighting default concentration across loan bands.

**Insight:** Medium and High loan sizes form major exposure pockets.

---

### 🔹 Interest Rate Analysis

**4️⃣ Loan Status Distribution by Interest Band**  
Higher interest bands show visibly higher charged-off volumes.

**5️⃣ Default Rate by Interest Rate Band**

| Interest Band | Default Rate |
|---------------|--------------|
| Low | 3.67% |
| Medium | 9.01% |
| High | 17.31% |
| Very High | 27.56% |

Default risk increases consistently with higher interest rates.

**6️⃣ Total Loans by Interest Band (Donut Chart)**  
- Medium band has highest portfolio exposure  
- Very High band holds ~22% of total loans  
- Clear risk concentration pockets visible  

---

## 📈 Key Analytical Findings  

### 1️⃣ Interest Rate is a Strong Risk Driver  
Default rate rises sharply from Low to Very High bands.  
Very High band default is nearly 7× Low band.

### 2️⃣ Loan Size Impacts Default  
Higher loan amounts show elevated default behavior.  
Large-ticket lending increases exposure risk.

### 3️⃣ Portfolio Risk Concentration  
Medium and High segments form bulk exposure.  
Very High segments show high severity despite lower volume.

### 4️⃣ Employment Length  
Variation across employment categories is limited.  
Financial variables outperform demographic factors in predicting risk.

---

## 🧠 Risk Segmentation Strategy  

Segmentation built using:
- Interest Rate Band  
- Loan Amount Band  
- Default Status  

### High-Risk Cluster Identified:
**Very High Interest Band + Higher Loan Amount**

This combination creates concentrated default pockets.

---

## 💡 Business Recommendations  

1. Tighten approvals in Very High interest band  
2. Cap exposure in higher loan amount segments  
3. Introduce stricter DTI & utilization thresholds  
4. Develop a Probability-of-Default (PD) model  
5. Implement risk-based pricing  

---

## 📉 Impact Estimation  

If exposure to the Very High band reduces by 25%:

→ Portfolio default rate may decline by **1–2 percentage points**

### Expected Benefits
- Reduced credit losses  
- Lower provisioning requirements  
- Improved ROA  
- Better capital efficiency  
- Stronger risk-adjusted returns  

---

## ⚠️ Limitations  

- No macroeconomic control variables  
- No LGD/EAD modeling  
- Descriptive analysis (no predictive modeling)  
- Period-specific data snapshot  

---

## 🚀 Future Scope  

- Build ML-based credit scoring model  
- Estimate PD, LGD, and EAD  
- Integrate bureau data  
- Automate risk monitoring dashboard  

---

## 🛠 Tools Used  

- Google Sheets  
- Pivot Tables  
- KPI Dashboard Design  
- Data Cleaning & Feature Engineering  

---

## 📌 Final Conclusion  

Interest Rate Band and Loan Size are strong predictors of default concentration.

Structured segmentation enables:
- Smarter credit approvals  
- Reduced exposure concentration  
- Improved portfolio profitability  

---

> Academic Capstone Project – Banking & Financial Services Analytics

