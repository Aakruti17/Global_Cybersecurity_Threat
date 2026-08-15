# 🌐 Global Cybersecurity Threats Dashboard (2015–2024)

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-Data%20Visualization-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI">
  <img src="https://img.shields.io/badge/Excel-Dataset-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" alt="Excel">
  <img src="https://img.shields.io/badge/Cybersecurity-Analytics-0A66C2?style=for-the-badge&logo=datadog&logoColor=white" alt="Cybersecurity">
  <img src="https://img.shields.io/badge/Data%20Analytics-Project-6C63FF?style=for-the-badge" alt="Data Analytics">
</p>

<p align="center">
  <b>Interactive Power BI Dashboard for analyzing global cybersecurity incidents, financial losses, affected users, attack types, industries, and countries from 2015 to 2024.</b>
</p>

---

## 📌 Project Overview

Cybersecurity attacks have become a major global concern, affecting individuals, organizations, industries, and governments.

This project presents an **interactive Global Cybersecurity Threats Dashboard** developed using **Microsoft Power BI**.

The dashboard analyzes cybersecurity incidents recorded between **2015 and 2024** and provides insights into:

- 🌍 Countries affected by cyber attacks
- 🎯 Different types of cyber attacks
- 🏢 Industries targeted
- 💰 Financial losses caused by attacks
- 👥 Number of affected users
- 🕵️ Attack sources
- ⏱️ Incident resolution time
- 🔐 Security vulnerabilities
- 🛡️ Defense mechanisms

The main objective is to transform raw cybersecurity data into meaningful visual insights that can support **security analysis, risk assessment, and strategic decision-making**.

---

# 📊 Dashboard Preview

## 🖥️ Dashboard Page 1 — Global Cybersecurity Overview

<p align="center">
  <img src="./images/dashboard-page-1.png" alt="Global Cybersecurity Dashboard Page 1" width="100%">
</p>

### Key Features

- KPI cards for major cybersecurity metrics
- Attack source analysis
- Attack type distribution
- Financial loss by attack type
- Country slicer
- Attack type slicer
- Interactive filtering

---

## 🖥️ Dashboard Page 2 — Financial Loss Analysis

<p align="center">
  <img src="./images/dashboard-page-2.png" alt="Global Cybersecurity Dashboard Page 2" width="100%">
</p>

### Key Features

- Financial loss by industry
- Financial loss by country
- Geographical cybersecurity analysis
- Industry-wise financial impact
- Country and attack-type filters
- Treemap visualization

---

## 🖥️ Dashboard Page 3 — Affected Users & Detailed Analysis

<p align="center">
  <img src="./images/dashboard-page-3.png" alt="Global Cybersecurity Dashboard Page 3" width="100%">
</p>

### Key Features

- Affected users by country
- Financial loss vs affected users
- Country-wise distribution
- Detailed cybersecurity incident table
- Interactive country filtering
- Interactive attack-type filtering

---

# 🎯 Project Objectives

The primary objectives of this project are:

1. Analyze global cybersecurity incidents from 2015 to 2024.
2. Identify the most common types of cyber attacks.
3. Determine which industries experience the highest financial losses.
4. Analyze the countries most affected by cyber attacks.
5. Measure the number of users impacted by cybersecurity incidents.
6. Identify major attack sources.
7. Analyze incident resolution time.
8. Provide interactive filtering for deeper analysis.
9. Convert raw cybersecurity data into an easy-to-understand business dashboard.
10. Support cybersecurity risk analysis through data visualization.

---

# 📁 Dataset Information

The dataset contains **3,000 cybersecurity incident records** covering the period **2015–2024**.

### Dataset Columns

| Column | Description |
|---|---|
| `Country` | Country where the cybersecurity incident occurred |
| `Year` | Year of the incident |
| `Attack Type` | Type of cyber attack |
| `Target Industry` | Industry affected by the attack |
| `Financial Loss (in Million $)` | Financial loss caused by the incident |
| `Number of Affected Users` | Number of users affected |
| `Attack Source` | Source/origin of the attack |
| `Security Vulnerability Type` | Vulnerability exploited |
| `Defense Mechanism Used` | Security mechanism used against the attack |
| `Incident Resolution Time (in Hours)` | Time required to resolve the incident |

---

# 📈 Dataset Summary

| Metric | Value |
|---|---:|
| 📌 Total Records | 3,000 |
| 🌍 Countries | 10 |
| 📅 Time Period | 2015–2024 |
| 🎯 Attack Types | 6 |
| 🏢 Industries | 7 |
| 🕵️ Attack Sources | 4 |
| 🔓 Vulnerability Types | 4 |
| 🛡️ Defense Mechanisms | 5 |
| 👥 Total Affected Users | ~1.51 Billion |
| 💰 Total Financial Loss | $151.48 Billion |
| ⏱️ Average Resolution Time | ~36.48 Hours |

> **Note:** Financial loss in the dataset is stored in **Million USD**.  
> Therefore, `151,478.91 Million USD ≈ $151.48 Billion USD`.

---

# 📌 Key Performance Indicators (KPIs)

The dashboard provides the following major KPIs:

### 👥 Total Affected Users

Measures the total number of users impacted by cybersecurity incidents.

```DAX
Total Affected Users =
SUM('Global Cybersecurity Threats'[Number of Affected Users])
