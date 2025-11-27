# 🎬 Movie Industry Data Analysis Project 

-----

## ✨ Project Overview

This project involves an end-to-end data analysis workflow on a comprehensive dataset of movies. The primary goal is to **explore the dataset, clean the data, and analyze key factors that correlate with a movie's financial success (Gross Revenue)**.

The analysis utilizes Python for data manipulation, cleaning, statistical analysis, and visualization to derive actionable insights into the movie industry.

-----

## ⚙️ Dependencies and Setup

To run this notebook locally, you need a Python environment with the following libraries installed.

### 🐍 Requirements

The core analysis relies on the following Python libraries:

  * **pandas**
  * **numpy**
  * **seaborn** (for statistical data visualization)
  * **matplotlib** (for plotting and visualization)

You can install all necessary packages using `pip`:

```bash
pip install pandas numpy seaborn matplotlib
```

### 📁 Data Source

The analysis is based on a local CSV file named `movies.csv`.

-----

## 🚀 Key Features and Methodology

The project follows standard data science practices, focusing on robust data cleaning and statistical correlation analysis.

### 🧹 Data Cleaning and Preprocessing

The dataset consists of **7,668 records and 15 columns**. The cleaning process addressed missing values and duplicates:

  * **Handling Missing Values:**
      * The `budget` column (28% missing) and `gross` column (2% missing) were imputed using their **median** values.
      * The `rating` column was imputed using the **mode** (most frequent value).
      * The `company` column was filled with the string **'Unknown'**.
      * `score`, `votes`, and `runtime` were also filled using their respective **median** values.
  * **Duplicate Handling:** Duplicate entries were identified and removed from the dataset.

### 📊 Exploratory Data Analysis (EDA)

  * Visualizations were generated using **Seaborn and Matplotlib** to explore the relationships between key numerical variables.
  * A specific focus was placed on visualizing the correlation between **Budget and Gross Revenue** using a scatter plot.

### 📈 Correlation Analysis

  * The project calculated correlation matrices using different methods (**Pearson, Kendall, and Spearman**) to accurately assess linear relationships between numerical features, such as `budget`, `gross`, `score`, and `votes`.
  * Heatmaps were generated to visualize the strength and direction of these correlations.

-----

## 🎯 Key Insights

The analysis yielded several key statistics and insights into the dataset:

| Statistic | Value |
| :--- | :--- |
| **Average Movie Score** | 6.39 |
| **Average Budget** | $25,074,890.02 |
| **Average Gross Revenue** | $48,935,213.79 |
| **Highest Grossing Movie** | *Star Wars: Episode V - The Empire Strikes Back* |
| **Top Earning Genre (by average gross)** | Animation |

The correlation analysis also revealed important relationships:

  * There is a strong correlation between a movie's **Budget** and its **Gross Revenue**.
  * A movie's **Votes** count is highly correlated with its **Gross Revenue**.
  * Other variables, like **Score**, also show a positive correlation with Gross Revenue.



  * **Predictive Modeling:** Build a machine learning model to predict a movie's `gross` revenue based on its `budget`, `score`, and other features.
