# 🏠 Airbnb NYC Listings Analysis
### A Comprehensive Data Analysis Project

---

## 📋 Project Overview

This comprehensive data analysis project explores Airbnb listing data from New York City, providing deep insights into the short-term rental market. Through extensive exploratory data analysis (EDA), we uncover patterns in pricing, availability, host behaviors, and guest preferences across the five boroughs.

**This project was developed as part of the Digilians Initiative, under the supervision of the Ministry of Communication and Information Technology (MCIT) and the Egyptian Military Academy.**

---

## 🎯 Objectives

- Analyze the distribution and characteristics of Airbnb listings across NYC
- Identify key factors influencing pricing and occupancy rates
- Uncover patterns in host behavior and listing performance
- Provide actionable insights for hosts, guests, and market analysts
- Demonstrate advanced data analysis and visualization techniques

---

## 📊 Dataset Overview

The dataset contains **102,599 Airbnb listings** with **26 features** covering:

- **Listing Information**: ID, name, room type, pricing, availability
- **Host Details**: Host ID, verification status, listing count
- **Location Data**: Neighborhood groups (boroughs), latitude, longitude
- **Review Metrics**: Number of reviews, ratings, review frequency
- **Policies**: Cancellation policies, instant bookability

---

## 🔍 Key Findings & Insights

### 🏘️ Geographic Distribution
- **Manhattan** dominates with the highest concentration of listings
- **Brooklyn** follows as the second most popular borough
- Strong correlation between location and pricing patterns

### 💰 Pricing Analysis
- **Entire homes/apts** command premium prices vs. private/shared rooms
- **Manhattan** listings average significantly higher rates
- Clear relationship between price and reviews/ratings

### 📈 Host Behavior
- Most hosts operate **single listings** (1-2 properties)
- Verified hosts tend to have better reviews and higher occupancy
- Host verification status shows correlation with listing quality

### ⭐ Guest Preferences
- **Entire homes/apts** most popular room type
- Reviews per month strongly correlated with listing popularity
- Higher-rated listings show better availability patterns

---

## 🛠️ Technologies Used

| Category | Tools/Libraries |
|----------|----------------|
| **Data Processing** | Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn, WordCloud |
| **Geographic Analysis** | Folium |
| **Statistical Analysis** | Correlation matrices, Distribution analysis |
| **Development** | Python 3.8+, Jupyter Notebooks |

---

## 📈 Visualizations Included

1. **Host Analysis**
   - Host verification status distribution
   - Listings per host histogram
   
2. **Property Analysis**
   - Room type distribution
   - Construction year analysis
   - House rules word cloud

3. **Price Analysis**
   - Price distribution by room type
   - Price by neighborhood group
   - Price vs. reviews scatter plot

4. **Geographic Analysis**
   - Interactive Folium map of listings
   - Top neighborhoods by listing count

5. **Review & Rating Analysis**
   - Number of reviews distribution
   - Reviews per month analysis
   - Review rate distribution
   - Days since last review analysis

6. **Booking & Availability**
   - Instant bookable listings
   - Availability 365 distribution
   - Cancellation policy distribution

7. **Advanced Analytics**
   - Correlation heatmap
   - Top 10 listings by estimated revenue

---

## 💡 Key Business Insights

### For Hosts
- **Manhattan** offers highest revenue potential but faces more competition
- **Instant bookable** listings show higher occupancy rates
- **Verified hosts** command 15-20% higher prices on average
- **Entire homes** generate 3x revenue of shared rooms

### For Guests
- Best value found in **outer boroughs** (Queens, Staten Island)
- **Flexible cancellation** policies correlate with higher ratings
- **Recent reviews** indicator of active, well-maintained properties

### Market Trends
- **2015-2019** saw peak listing growth
- **Entire homes** dominate the market (65% of listings)
- **Flexible cancellation** most popular policy (45%)

---

## 🚀 Installation & Setup

```bash
# Clone the repository
git clone https://github.com/yourusername/airbnb-nyc-analysis.git

# Install required packages
pip install pandas numpy matplotlib seaborn folium wordcloud

# Launch Jupyter Notebook
jupyter notebook AirBnB_Project.ipynb
```

## 📁 Project Structure

```
airbnb-nyc-analysis/
│
├── AirBnB_Project.ipynb          # Main analysis notebook
├── Airbnb_Open_Data.csv          # Dataset                                  
└──  README.md                    # Project documentation
```

---

## 📊 Sample Code Snippet

```python
# Loading and initial exploration
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

df = pd.read_csv("Airbnb_Open_Data.csv")
print(f"Dataset shape: {df.shape}")
print(f"Features: {df.columns.tolist()}")
```

---

## 🎓 Learning Outcomes

- **Data Cleaning & Preprocessing**: Handling missing values, outliers, and data type conversions
- **Exploratory Data Analysis**: Statistical analysis and pattern recognition
- **Data Visualization**: Creating meaningful visual representations
- **Geographic Analysis**: Mapping and spatial data visualization
- **Business Intelligence**: Translating data insights into actionable recommendations

---

---

## 📚 References

- Airbnb Open Data: [Kaggle Dataset](https://www.kaggle.com/datasets/arianazmoudeh/airbnbopendata)
- NYC Borough Boundaries: NYC Open Data
- [Pandas Documentation](https://pandas.pydata.org/)
- [Seaborn Documentation](https://seaborn.pydata.org/)

---

## 📬 Contact

For questions, collaborations, or feedback:

- **Email**: dinaelharedy00@gmail.com
- **LinkedIn**: [My Profile](https://www.linkedin.com/in/dina-ali-0573a724b/)

---

**© 2026 Digilians Initiative | Ministry of Communication and Information Technology | Egyptian Military Academy**

---

*This project represents a significant milestone in the Digilians training program, demonstrating proficiency in data analysis, visualization, and deriving actionable insights from complex datasets.*
