# 📊 Insurance Claims Pattern Visualization & Analytics Dashboard

[![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white)](https://www.tableau.com/)
[![GitHub repo](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github)](https://github.com/aasritha25/Insurance-Claims-Pattern-Visualization)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)](#)

An interactive, end-to-end **Business Intelligence & Data Visualization Dashboard** built in **Tableau** to uncover patterns, financial exposure, risk concentrations, and fraud indicators across auto insurance claims.

---

## 🖼️ Dashboard Preview

![Insurance Claims Pattern Dashboard](Insurance%20Claims%20Pattern%20Dashboard.png)

---

## 📖 Project Description & Objectives

In the insurance industry, claims processing and risk underwriting rely heavily on identifying behavioral anomalies, spatial loss concentrations, and cost distribution patterns. With thousands of claims processed annually, raw tabular datasets often obscure critical operational insights and fraud vectors.

This project delivers an in-depth exploratory data analysis and executive-ready visual dashboard developed in **Tableau**. It integrates claims records across multiple dimensions—including policyholder demographics, collision severities, vehicle manufacturers, geographic incident locations, and payout structures.

### 🎯 Core Objectives
- **Financial Exposure Mapping:** Dissect total claimed liabilities into distinct component costs (vehicle damage, bodily injuries, property damage).
- **Fraud Anomaly Detection:** Track the incidence of reported fraud (~24.7%) and correlate it with incident severity, policy duration, and deductible choices.
- **Demographic & Behavioral Profiling:** Analyze driver age distributions and vehicle makes (Dodge, Subaru, Saab, Ford, Chevrolet, etc.) to uncover high-frequency loss profiles.
- **Geographic Pattern Recognition:** Monitor incident density across cities (Arlington, Columbus, Hillsdale, Northbend, Northbrook, Riverwood, Springfield) to support localized risk pricing.

---

## 📌 Executive Summary & Key Performance Indicators (KPIs)

The dashboard provides a bird's-eye view of insurance claim distribution, cost drivers, and operational risk metrics across policyholders:

| KPI Metric | Value | Description |
| :--- | :--- | :--- |
| 💰 **Total Claim Amount** | **$52,761,940** | Total claims incurred across all reported incidents |
| 🚗 **Vehicle Claims** | **$37,928,950** | Vehicle damage costs (~71.9% of total claims portfolio) |
| 🏥 **Injury Claims** | **$7,433,420** | Bodily injury compensation payouts |
| 📄 **Annual Premiums** | **$1,256,406** | Total annual policy premiums collected |
| 🚨 **Fraud Rate** | **24.70%** | Proportion of investigated claims flagged with suspected fraud |

### 🔍 Collision Highlights
- **Rear Collision:** 600 incidents *(highest frequency)*
- **Side Collision:** 580 incidents
- **Front Collision:** 481 incidents

---

## 🎯 Key Visualizations & Analysis Modules

The workbook breaks down claims data across multiple dimensions:

### 1. 👥 Scatter Plot: Policyholder Age vs. Total Claim Amount
- Explores whether older or younger drivers incur disproportionately high claim amounts.
- Highlights claim clustering between ages **25 and 55**, with claim values ranging from minimal minor damage up to \$100,000+.

### 2. 📊 Severity vs. Injury Claim (Bar Chart)
- Examines bodily injury payouts against incident severity categories:
  - **Major Damage** & **Minor Damage** represent the bulk of injury compensation payouts (exceeding \$2M each).
  - **Total Loss** claims contribute significant secondary injury payouts.
  - **Trivial Damage** incurs negligible bodily injury expenses.

### 3. 🚙 Claims by Vehicle Make (Treemap)
- Visualizes cumulative claim exposure categorized by vehicle manufacturers.
- **Top Claim Contributors:**
  - **Dodge:** $32,01,250
  - **Subaru:** $31,12,420
  - **Saab:** $29,70,140
  - **Ford:** $29,52,810
  - **Chevrolet:** $29,27,230
  - **Nissan:** $29,27,130
  - *Followed by BMW, Audi, Acura, Jeep, Toyota, and Honda.*

### 4. 📈 Incident Type vs. Bodily Injuries (Bubble / Scatter Chart)
- Assesses bodily injury counts against specific incident classes (Multi-vehicle Collision, Single-vehicle Collision, Parked Car, Vehicle Theft).

### 5. 📦 Severity vs. Total Claim Amount (Box & Whisker Plot)
- Displays statistical dispersion, median claim values, and interquartile ranges (IQR).
- Identifies claim outliers and variance across **Major Damage**, **Minor Damage**, **Total Loss**, and **Trivial Damage**.

### 6. 🏙️ Geographic Trends Across Cities (Line Chart)
- Tracks claim volume fluctuations and monetary spikes across key municipalities:
  - **Arlington, Columbus, Hillsdale, Northbend, Northbrook, Riverwood, Springfield**.
  - Pinpoints specific peak hours and localized incident clusters.

---

## 💡 Key Business Insights

1. **Vehicle Loss Dominates Claims Costs:**  
   Over 71% of total claim expenditure stems directly from vehicle damage (\$37.9M+ out of \$52.7M), suggesting that subrogation recovery and repair network optimizations offer the highest cost-saving potential.

2. **Critical Fraud Exposure:**  
   With an overall fraud rate of **24.70%**, almost 1 in every 4 claims displays fraudulent flags, highlighting the necessity for automated fraud detection models at First Notice of Loss (FNOL).

3. **Collision Impact Patterns:**  
   Rear-end collisions (600) and side collisions (580) significantly outpace frontal impacts, driving high-frequency minor to major injury payouts.

---

## 📂 Repository Contents

```text
Insurance-Claims-Pattern-Visualization/
│
├── Insurance Claims Pattern Dashboard.png       # High-resolution dashboard capture
├── Insurance Claims Pattern Visualization.twb   # Interactive Tableau Workbook file
└── README.md                                    # Project documentation and summary
```

---

## 🚀 How to View and Interact with the Dashboard

### Prerequisites
- **Tableau Desktop** or **Tableau Public** (v2020.1 or newer). Download free at [Tableau Public](https://public.tableau.com/).

### Steps
1. **Clone the repository:**
   ```bash
   git clone https://github.com/aasritha25/Insurance-Claims-Pattern-Visualization.git
   ```
2. **Open the Workbook:**
   - Double-click `Insurance Claims Pattern Visualization.twb` or open it directly inside Tableau Desktop / Tableau Public.
3. **Data Source:**
   - The underlying dataset is based on auto insurance claims (`insurance_claims.csv`), containing 39 attributes including policyholder profiles, incident locations, collision severities, and claim breakdown amounts.

---

## 🛠️ Built With

- **[Tableau Desktop / Tableau Public](https://www.tableau.com/)** – Interactive Dashboard Design & Visual Storytelling
- **Statistical Chart Types:** Box & Whisker Plots, Treemaps, Time-Series Line Charts, Scatter Plots, Bar Charts, KPI Scorecards

---

## 👤 Author

**Aasritha**
- GitHub: [@aasritha25](https://github.com/aasritha25)
- Repository: [Insurance-Claims-Pattern-Visualization](https://github.com/aasritha25/Insurance-Claims-Pattern-Visualization)

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
