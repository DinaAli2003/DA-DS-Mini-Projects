# 🎓 Student Performance: End-to-End Analytics

## 📌 Executive Summary

This project delivers a comprehensive, end-to-end data analysis of the factors influencing academic success. By processing a dataset of **6,607 students**, I leveraged statistical modeling and data visualization to uncover the behavioral and socio-economic drivers behind exam outcomes.

Developed as a core requirement for the **Digilians 9-Month Specialized Diploma**, this repository demonstrates advanced data cleaning, exploratory data analysis (EDA), and insight communication.

---

## 🛠 Tech Stack & Tools

* **Core Logic:** `Python`
* **Data Wrangling:** `Pandas`, `NumPy.`
* **Visualization:** `Seaborn`, `Matplotlib` (Customized styling for readability)
* **Environment:** Jupyter Notebook / VS Code

---

## 📊 The Data Landscape

The dataset consists of **20 features** capturing the holistic student experience:

| Category | Key Variables |
| --- | --- |
| **Academic** | `Hours_Studied`, `Attendance`, `Tutoring_Sessions`, `Previous_Scores` |
| **Physical/Mental** | `Sleep_Hours`, `Physical_Activity`, `Motivation_Level` |
| **Socio-Economic** | `Family_Income`, `Internet_Access`, `Teacher_Quality`, `Parental_Involvement` |
| **Target** | **`Exam_Score`** |

---

## 🚀 The Data Pipeline

### 1. Data Integrity (Cleaning)

* **Missing Value Strategy:** Implemented **Mode Imputation** for categorical gaps to maintain the statistical significance of the 6,607 records.
* **Consistency Checks:** Validated data types and removed anomalies to ensure "Garbage In, Garbage Out" was avoided.

### 2. Exploratory Data Analysis (EDA)

I moved beyond basic plotting to analyze **correlations** and **feature interactions**:

* **Linear Trends:** Analyzed the direct correlation between `Hours_Studied` and `Exam_Score`.
* **Categorical Impact:** Used **Box Plots** to visualize how `Parental_Involvement` shifts the median performance of students.
* **Multivariate Analysis:** Explored the synergy between `Attendance` and `Previous_Scores`.

---

## 🧠 Strategic Insights

* 📈 **The Attendance Factor:** Attendance emerged as one of the strongest indicators of success, surpassing physical activity.
* 👨‍👩‍👧 **The Support Loop:** High levels of parental involvement and motivation levels show a statistically significant "lift" in average scores.
* 💻 **Digital Divide:** Students with internet access consistently outperformed those without, highlighting the importance of digital resources.

---

## 📂 Project Structure

```text
├── data/
│   └── StudentPerformanceFactors.csv   # Raw Dataset
├── notebooks/
│   └── student_analysis_main.ipynb     # Full Analysis & Visuals
├── README.md                           # Project Documentation
└── requirements.txt                    # Project Dependencies

```

---

## 🤝 Acknowledgments

This project was completed under the specialized training framework of the **Ministry of Communications and Information Technology (MCIT)**, in collaboration with the **Egyptian Military Academy**, as part of the Digilians Initiative.




