# 🏡 Airbnb Listings Data Analysis Project

## 📌 Project Overview

This project presents a complete end-to-end data analysis of an Airbnb-style listings dataset.
The objective is to extract actionable business insights, optimize pricing strategies, analyze host performance, and identify revenue growth opportunities using Python and data analytics techniques.

The analysis includes:

* Data Cleaning & Preprocessing
* Handling Missing Values & Outliers
* Exploratory Data Analysis (EDA)
* Geographical & Pricing Insights
* Host & Review Analysis
* Revenue Estimation
* Business Recommendations

---

# 📂 Dataset Description

The dataset contains **5,226 listings** with information about:

* Listing details (name, room type, minimum nights)
* Host information (verification status, listings count)
* Location (latitude, longitude, neighbourhood)
* Pricing (price, service fee)
* Reviews (number of reviews, rating, reviews per month)
* Availability (365-day availability)
* Cancellation policies
* Property construction year

---

# 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Folium (for maps)
* WordCloud

---

# 🔄 Data Cleaning & Preprocessing

The following steps were performed:

### ✅ 1. Removed Irrelevant Columns

* Dropped `license` column (100% null values).

### ✅ 2. Handled Missing Values

* Categorical columns → Filled with `"Unknown"` or mode.
* Numerical columns → Imputed with median values.
* Converted `last review` to datetime format.

### ✅ 3. Cleaned Price Columns

* Removed `$` and commas from `price` and `service fee`.
* Converted them to numeric types.

### ✅ 4. Removed Duplicates

* Removed duplicate listings using `id`.

### ✅ 5. Outlier Treatment

* Capped extreme values in:

  * `price`
  * `minimum nights`

---

# 📊 Exploratory Data Analysis (EDA)

## 1️⃣ Host Analysis

* Distribution of verified vs non-verified hosts.
* Number of listings per host.
* Identification of high-volume hosts.

### 🔎 Key Insight:

Verified hosts increase platform trust and may influence booking decisions.

---

## 2️⃣ Room & Listing Analysis

* Room type distribution.
* Price comparison across room types.
* Minimum nights distribution.
* Property construction year analysis.
* Word cloud of common house rules.

### 🔎 Key Insight:

Entire homes command higher prices, while private/shared rooms drive affordability and occupancy.

---

## 3️⃣ Pricing Analysis

* Price distribution and outlier detection.
* Price comparison by:

  * Room type
  * Neighbourhood group
* Correlation between price and:

  * Reviews
  * Availability
  * Host listing count

### 🔎 Key Insight:

Location and room type are major drivers of pricing.

---

## 4️⃣ Geographic Analysis

* Top neighbourhoods by listing count.
* Interactive map visualization using latitude and longitude.
* High-density areas identification.

### 🔎 Key Insight:

Certain neighbourhoods dominate the market and offer premium pricing opportunities.

---

## 5️⃣ Reviews & Ratings Analysis

* Distribution of number of reviews.
* Reviews per month trend.
* Review rating distribution.
* Days since last review analysis.

### 🔎 Key Insight:

Listings with higher reviews per month show stronger revenue potential.

---

## 6️⃣ Booking & Availability Analysis

* Instant bookable listings distribution.
* Availability over 365 days.
* Cancellation policy patterns.

### 🔎 Key Insight:

High availability may indicate low occupancy; dynamic pricing is recommended.

---

# 💰 Revenue Estimation

An estimated revenue metric was created:

```
Estimated Revenue = Price × Availability 365 × Reviews per Month
```

This helped identify:

* Top-performing listings
* Revenue-driving patterns
* Characteristics of successful properties

---

# 📈 Correlation Analysis

A correlation heatmap was generated to analyze relationships between:

* Price
* Reviews
* Service fee
* Minimum nights
* Availability
* Host listing count

---

# 📌 Business Recommendations

Based on the analysis:

### 1️⃣ Implement Dynamic Pricing

Adjust prices based on:

* Location demand
* Room type
* Reviews & rating
* Availability levels

---

### 2️⃣ Encourage Host Verification

Verified hosts increase trust and booking confidence.

---

### 3️⃣ Promote Instant Booking

Boost visibility for instant-bookable listings.

---

### 4️⃣ Optimize Underperforming Listings

For listings with:

* High availability
* Low reviews

→ Recommend price adjustments and marketing improvements.

---

### 5️⃣ Focus on High-Demand Neighbourhoods

Invest marketing efforts in premium areas while supporting growth in underperforming locations.

---

# 🚀 Project Outcomes

This project demonstrates:

* Strong data cleaning skills
* Advanced exploratory data analysis
* Business-oriented insight extraction
* Data-driven decision making
* Revenue optimization thinking

---

# 📎 How to Run the Project

```bash
git clone https://github.com/your-username/airbnb-analysis.git
cd airbnb-analysis
pip install -r requirements.txt
python airbnb_analysis.py
```

Or open the Jupyter Notebook:

```bash
jupyter notebook
```

---

# 📌 Future Improvements

* Build a Price Prediction Machine Learning model
* Develop a Booking Probability Model
* Deploy an interactive dashboard (Streamlit / Power BI)
* Implement clustering for market segmentation



