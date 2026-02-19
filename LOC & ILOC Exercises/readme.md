# 🚀 Mastering `loc` & `iloc` in Pandas
 
Hello and welcome! This repository contains the solutions for two hands-on assignments focused on one of the most fundamental skills in data analysis with Python: **selecting and filtering data using `.loc` and `.iloc` in the Pandas library.**

These assignments were completed as part of the **Digilians initiative**, a prestigious program under the joint supervision of the **Egyptian Ministry of Communications and Information Technology (MCIT)** and the **Egyptian Military Academy**. Our goal is to build a generation of digital experts, and this work represents a key step in mastering data manipulation techniques.

This README will guide you through the assignments, the concepts covered, and how to run the code yourself.

## 📝 Assignments Overview

This project consists of two Jupyter Notebooks, each designed to build your proficiency with Pandas in a practical way.

### **Assignment 1: `DA ILOC &LOC Assignment1.ipynb` - Orders Dataset**
This notebook serves as a gentle and comprehensive introduction. You'll start from scratch by creating a simple dataset and then progress through a wide array of selection and filtering techniques.

*   **Core Skills:**
    *   Creating a Pandas DataFrame from a Python dictionary.
    *   Exporting data to a CSV file and reading it back.
    *   Mastering `.iloc` for **integer-location based indexing** (selecting rows and columns by their numerical position).
    *   Mastering `.loc` for **label-based indexing** and conditional filtering.
    *   Performing basic data manipulation like updating values.
*   **Key Operations:** Selecting first/last rows, slicing, conditional selections (City = Cairo, Amount > 300), updating values, and sorting.
*   **Date/Time Functionality:** The notebook also introduces advanced date-based filtering, such as selecting orders by month, day of the week, and the last day of the month. This is crucial for time-series analysis!

### **Assignment 2: `DA ILOC AND LOC Assignment2.ipynb` - Diabetes Dataset**
In this assignment, we level up by applying our skills to a real-world medical dataset (Pima Indians Diabetes Database). The focus shifts to exploring data and answering clinical questions.

*   **Core Skills:**
    *   Loading a real-world dataset from a CSV file.
    *   Performing initial data exploration (`.shape`, `.info()`, `.describe()`).
    *   Applying `.loc` and `.iloc` for complex analytical queries.
    *   Data cleaning and transformation.
    *   Using `groupby` for insightful aggregations.
*   **Analytical Queries:** You'll learn to filter patients based on conditions like:
    *   Diabetic vs. non-diabetic patients.
    *   Patients with high glucose, high BMI, or specific age groups.
    *   Identifying potential data quality issues (e.g., zero values for Insulin).
*   **Feature Engineering:** Creating new columns like `AgeGroup` to categorize data for better analysis.

## 🛠️ Key Functions and Concepts Demonstrated

Here’s a quick reference of the powerful Pandas functions you'll see in action:

*   **`pd.DataFrame()`** : Create a DataFrame.
*   **`.iloc[]`** : Select rows and columns by **index position**.
    *   `df.iloc[:3]` -> First 3 rows.
    *   `df.iloc[-1]` -> Last row.
    *   `df.iloc[1:4, [1, 3]]` -> Rows 1-3 and columns 2 & 4.
*   **`.loc[]`** : Select rows and columns by **label** or **boolean condition**.
    *   `df.loc[df["City"] == "Cairo"]` -> Rows where City is Cairo.
    *   `df.loc[df["Amount"] > 300, ["Customer", "Amount"]]` -> Specific columns for high-value orders.
*   **Conditional Filtering:** Using `&` (AND), `|` (OR), `~` (NOT), and `.isin()`.
*   **String Methods:** `.str.startswith("M")` to find customers whose names start with 'M'.
*   **Date/Time Operations:** Using `.dt` accessor to extract `month`, `day`, `day_name()`.
*   **`sort_values()`** : Sorting data.
*   **`groupby()`** : Splitting data into groups to apply functions like `sum`, `mean`, `size`, and `first`.
*   **`pd.cut()`** : Binning numerical data into categorical labels (e.g., creating `AgeGroup`).

## 📁 Repository Structure

```
.
├── README.md                   # You are here!
├── DA ILOC &LOC Assignment1.ipynb  # Assignment 1 Notebook
├── DA ILOC AND LOC Assignment2.ipynb # Assignment 2 Notebook
├── orders.csv                  # CSV file generated in Assignment 1
└── Diabetes Dataset.csv        # Dataset used in Assignment 2
```

## ⚙️ How to Run the Code

1.  **Clone the Repository:** (If you have it on GitHub)
    ```bash
    git clone <your-repository-url>
    cd <repository-name>
    ```
2.  **Install Dependencies:** You'll need Python and Pandas installed. It's best to use a virtual environment.
    ```bash
    pip install pandas numpy jupyter
    ```
3.  **Launch Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
4.  **Open and Run:** Navigate to the desired `.ipynb` file and run the cells sequentially (Shift + Enter).

## 🎯 Conclusion

These assignments are a fantastic foundation for any aspiring data analyst. By completing them, you've gained practical experience in the core data manipulation techniques that are used daily in the field.

The journey from creating a simple list of orders to querying a medical dataset for high-risk patients perfectly mirrors the path of a real-world analyst: starting with basic tools and gradually applying them to solve more complex problems.
