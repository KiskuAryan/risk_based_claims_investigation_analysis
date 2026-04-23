#  Risk-Based Claims Investigation Analysis

##  Overview

This project analyzes insurance claim data to identify high-risk cases and estimate potential savings through targeted investigation.

Instead of investigating all claims, this dashboard demonstrates how focusing on high-risk segments can significantly reduce financial losses.

---

##  Objectives

* Identify high-risk claims contributing most to financial exposure
* Analyze the relationship between risk factors and claim amounts
* Estimate potential savings based on investigation effort
* Optimize investigation strategy using data-driven insights

---

##  Key Insights

* High-risk claims contribute the majority of total claim amount
* Investigating top ~40–50% of claims captures a significant portion of potential savings
* Beyond this threshold, savings increase at a diminishing rate
* Lower credit scores are associated with higher claim amounts

---

##  Dashboard Pages

### 1. Claims & Risk Overview

* Total claim amount, paid amount, outstanding amount
* Risk segmentation analysis
* Driving behavior impact on financial risk

### 2. Risk & Claim Analysis

* Relationship between credit score and claim amount
* Trend analysis to identify risk patterns

### 3. Reconciliation Analysis

* Error detection and mismatch percentage
* Financial impact of discrepancies
* Identification of high-risk problematic cases

### 4. Investigation Impact Analysis

* Interactive slider to simulate investigation effort
* Savings curve showing diminishing returns
* Optimal investigation range (~40–50%)

---

##  Methodology

* Claims ranked based on risk indicators (e.g., risk level, discrepancies, driving record)
* Top N% claims selected dynamically using parameter-driven filtering
* Estimated savings calculated by aggregating high-risk claim amounts
* Sensitivity analysis performed using a What-If parameter

---

##  Tools Used

* Power BI
* DAX (Data Analysis Expressions)
* Data Visualization & Storytelling

---

##  Conclusion

Targeted investigation of high-risk claims is significantly more efficient than investigating all claims.
A data-driven approach helps reduce financial losses while optimizing operational effort.

---

##  Dashboard Preview

## 📊 Dashboard Preview

### 🔹 Overview
![Overview](screenshots/overview.png)

### 🔹 Investigation
![Investigation](screenshots/investigation.png)

### 🔹 Reconciliation
![Reconciliation](screenshots/reconciliation.png)

### 🔹 Credit Analysis
![Credit Analysis](screenshots/credit_analysis.png)
