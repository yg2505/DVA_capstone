# 📊 Loan Default Risk Analysis  
### A Study on Loan Preferences, Repayment Behavior & Default Risk

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

Financial institutions often struggle to clearly map borrower employment and financial characteristics to repayment behavior. Weak segmentation leads to higher default rates, inefficient credit allocation, and lower portfolio profitability.

This project analyzes **49,999 Lending Club loans** to identify risk drivers using:

- Data Cleaning  
- Feature Engineering  
- KPI Framework  
- Pivot Table Analysis  
- Interactive Dashboard (Google Sheets)  

---

## 🎯 Business Problem

Banks lack a structured, data-driven framework to connect borrower employment and financial signals with actual repayment outcomes.

### Objective
To identify high-risk segments and support:
- Smarter credit approvals  
- Risk-based pricing decisions  
- Improved portfolio profitability  

---

## 📂 Repository Structure


---

## 🛠 Data Engineering

### 📥 Data Source
- Lending Club Public Dataset (GitHub)
- 49,999 loan records
- ~30 variables
- Consumer unsecured loans

### 🧹 Data Cleaning (Google Sheets)

- Converted Interest Rate (%) from text to decimal  
- Standardized Employment Length categories  
- Created Risk Bands:
  - Interest Rate Band
  - Loan Amount Band
  - DTI Band
  - Revolving Utilization Band  
- Handled missing values  
- Assumptions:
  - **Charged Off = Default**
  - **Fully Paid = Successful repayment**

---

## 📊 KPI Framework

| KPI | Value | Business Meaning |
|------|--------|------------------|
| Total Loans | 49,999 | Portfolio size |
| Total Defaults | 7,579 | Risk exposure |
| Default Rate | 15.16% | Core risk indicator |
| Repayment Rate | 84.84% | Portfolio strength |
| High-Risk Exposure | 2.20% | Concentration risk |

These KPIs directly measure portfolio risk and segmentation efficiency.

---

## 📈 Key Insights

### 1️⃣ Interest Rate vs Default
- Low (<8%) → **3.67%**
- Very High (>16%) → **27.56%**

Default risk increases consistently with higher interest rates.

---

### 2️⃣ Credit Grade vs Default

| Grade | Default Rate |
|--------|--------------|
| A | 4.74% |
| B | 9.15% |
| C | 16.16% |
| D | 22.98% |
| E | 28.43% |
| F | 36.69% |
| G | 42.45% |

**Credit Grade is the strongest predictor of default.**

---

### 3️⃣ DTI Impact
- Very High DTI → **21.04% default**
- Low DTI → **11.87% default**

Higher debt burden increases repayment stress.

---

### 4️⃣ Revolving Utilization
- High (>75%) → ~16% default
- Low utilization → 12.73%

Credit overuse signals liquidity risk.

---

### 5️⃣ Employment Length
Default variation: 14.9% – 15.8%  
Relatively weaker predictor compared to financial indicators.

---

## 📊 Dashboard

Built using **Google Sheets** with:

### Executive View
- Total Loans
- Default Rate
- Repayment Rate
- Risk concentration overview

### Operational View
- Default by Grade
- Default by Interest Band
- DTI Segmentation
- Revolving Utilization Analysis
- Filters: Term, Grade, Employment Length

---

## 🧠 Advanced Risk Segmentation

A structured segmentation model was built using:

- Interest Rate Bands  
- Credit Grade  
- DTI Bands  
- Revolving Utilization Bands  

### Key Finding:
**Grade D–G + Very High Interest Band creates concentrated default pockets.**

This provides a clear risk-based approval strategy.

---

## ✅ Business Recommendations

1. Tighten approvals for Grade D–G  
2. Cap exposure in Very High interest band  
3. Introduce DTI & utilization thresholds  
4. Develop a Probability-of-Default (PD) scoring model  
5. Target low-risk borrowers for premium products  

---

## 💰 Impact Estimation

If approvals in the Very High risk band reduce by 25%:

→ Portfolio default rate may drop by **1–2 percentage points**

### Expected Benefits
- Reduced credit losses  
- Lower provisioning costs  
- Improved ROA  
- Better capital efficiency  
- Stronger risk-adjusted returns  

---

## ⚠️ Limitations

- No macroeconomic controls  
- No Loss-Given-Default estimation  
- Observational dataset (no causal inference)  
- Period-specific economic conditions  

---

## 🚀 Future Scope

- Build predictive credit scoring model  
- Integrate bureau data  
- Estimate LGD & EAD  
- Conduct pricing A/B testing  
- Deploy automated risk dashboard  

---

## 📌 Conclusion

Interest Rate and Credit Grade are dominant predictors of default risk.  
DTI and revolving utilization provide additional risk signals.  
Employment length has limited predictive strength.

Structured risk segmentation enables smarter lending decisions and improved portfolio performance.

---

### 📎 Tools Used
- Google Sheets  
- Pivot Tables  
- Data Cleaning & Feature Engineering  
- KPI Framework Design  

---

> Academic Capstone Project – Banking & Financial Services Analytics
