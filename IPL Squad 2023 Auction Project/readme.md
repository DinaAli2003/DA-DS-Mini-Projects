# 🏏 IPL 2023 Squad Strategy & Auction Analytics

## 📋 Project Context

This project was developed as part of the **Digilians Initiative**, conducted under the high-level supervision of the **Ministry of Communications and Information Technology (MCIT)** and the **Egyptian Military Academy**. It represents a professional application of data science to sports economics and franchise management.

## 🎯 Executive Summary

The Indian Premier League (IPL) auction is a complex financial marketplace where data-driven decision-making is vital for success. This project performs an end-to-end analysis of the **IPL 2023 Auction Dataset**, focusing on player valuation trends, team budget allocation, and recruitment efficiency.

The goal is to provide actionable insights for franchise managers to optimize their bidding strategies and squad composition.

## 🛠️ Technical Workflow

### 1. Data Cleaning & Engineering

To ensure high accuracy, the following preprocessing steps were implemented:

* **Duplicate Removal:** Identified and eliminated redundant entries to ensure data integrity.
* **Feature Engineering:** Created a `Price Multiplier` (Sold Price / Base Price) to quantify a player's market demand and a `Sold` status indicator for classification.
* **Monetary Standardization:** Cleaned the `Base Price` and `Cost` columns by removing currency symbols (₹, Cr) and converting them into numerical formats for calculation.
* **Missing Value Imputation:** Applied a statistical approach using **median** for numerical features and **mode** for categorical features to maintain dataset balance.

### 2. Exploratory Data Analysis (EDA)

The analysis explored several key dimensions of the 568-player dataset:

* **Price Distribution:** Visualized auction costs using Seaborn histplots to identify market skewness and high-value outliers.
* **Role Profiling:** Analyzed player categories (Batsman, Bowler, All-Rounder, Wicketkeeper) against their market valuation.
* **Retention Analysis:** Evaluated team stability by comparing current squads with 2022 rosters.

## 🚀 Key Strategic Recommendations

Based on the data findings, the following professional recommendations were established for future auctions:

1. **Base Price Optimization:** Align base prices with historical sale conversion rates to minimize the number of unsold players.
2. **Target High-Multiplier Profiles:** Focus scouting and investment on player profiles that historically trigger bidding wars.
3. **Strategic Role Allocation:** Direct larger portions of the budget toward high-conversion roles where demand consistently exceeds supply.
4. **Budget Risk Mitigation:** Diversify squad investments rather than over-relying on a few expensive "marquee" players to ensure squad depth.
5. **Retention Balance:** Maintain a core stability through retention while reserving 20-30% of the budget for high-impact tactical acquisitions at the auction table.

## 💻 Tech Stack

* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Environment:** Jupyter Notebook / Google Colab

---

### 🤝 Acknowledgement

This work is a testament to the advanced training provided by the **Digilians Initiative**. We extend our gratitude to the **Ministry of Communications and Information Technology** and the **Egyptian Military Academy** for their continued support in fostering digital excellence.

---

*For inquiries or collaboration regarding this analysis, please feel free to reach out.*
