# 💰 Smart Expense Tracker Application

> A simple, user-friendly Python application for recording, analyzing, filtering, and visualizing personal expenses.

---

## 📌 Project Overview

**Smart Expense Tracker** is a Python-based expense management application designed to help users keep track of their daily spending.

The application allows users to add, manage, analyze, filter, and visualize their expenses. It provides meaningful summaries and charts to help users understand their spending patterns.

This project demonstrates Python programming concepts along with **Object-Oriented Programming (OOP), NumPy, Pandas, Matplotlib, and Seaborn**.

---

## 🎯 Project Objectives

The main objectives of this project are:

1. To create a practical expense management application.
2. To store expense data in a structured CSV dataset.
3. To perform numerical calculations using NumPy.
4. To clean and analyze data using Pandas.
5. To demonstrate Object-Oriented Programming concepts.
6. To filter expenses based on different conditions.
7. To generate meaningful expense reports.
8. To identify spending patterns and major expense categories.
9. To visualize expenses using different charts.
10. To handle invalid inputs and empty data safely.

---

## ✨ Features

### ➕ Add Expense
Users can add a new expense by entering:
- Date
- Amount
- Category
- Description

The application validates the entered information before adding the expense.

### 👀 View Expenses
Displays all stored expense records in a structured table.

### 📊 Expense Summary
The application calculates:
- Total Expense
- Average Expense
- Highest Expense
- Lowest Expense
- Category-wise Expense

### 🔍 Filter Expenses
Users can filter expenses using:
- Category
- Start Date
- End Date
- Amount Range

### 📑 Generate Expense Report
The application generates a report containing:
- Number of expenses
- Total spending
- Average spending
- Category-wise spending
- Highest spending category

### 📅 Monthly Analysis
The application performs monthly expense analysis using Pandas.

### 📈 Data Visualization
The project includes four different visualizations:
1. **Bar Chart** — Total Expenses by Category
2. **Line Graph** — Spending Trends Over Time
3. **Pie Chart** — Expense Distribution by Category
4. **Histogram** — Frequency of Expense Amounts

### 💾 CSV Data Storage
Expense data is stored in `expenses.csv`.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| **Python** | Main programming language |
| **NumPy** | Numerical calculations and array operations |
| **Pandas** | Data loading, cleaning, filtering, grouping and analysis |
| **Matplotlib** | Data visualization |
| **Seaborn** | Statistical visualization |
| **CSV** | Data storage |
| **Jupyter Notebook** | Project development and execution |

---

## 🧠 Python Concepts Demonstrated

- Variables and Data Types
- Input and Output
- Conditional Statements
- Loops
- Functions
- Exception Handling
- Lists and Dictionaries
- File Handling
- CSV Handling
- Object-Oriented Programming
- Classes and Objects
- Methods
- NumPy Arrays
- Pandas DataFrames
- Data Filtering
- Data Grouping
- Data Aggregation
- Data Visualization

---

## 🏗️ Object-Oriented Programming

The project uses an `ExpenseTracker` class to organize expense management functionality.

### Main Methods

```text
add_expense()
get_summary()
filter_expenses()
generate_report()
```

The use of OOP makes the project organized, reusable, modular, and easier to maintain.

---

## 📂 Project Structure

```text
Smart_Expense_Tracker/
│
├── Smart_Expense_Tracker.ipynb
├── expenses.csv
└── README.md
```

### `Smart_Expense_Tracker.ipynb`
Contains the complete project implementation in Jupyter Notebook with separate cells.

### `expenses.csv`
Contains the expense dataset used by the application.

### `README.md`
Contains complete project documentation, features, technologies, and usage information.

---

## 📊 Dataset

The CSV dataset contains expense information.

| Column | Description |
|---|---|
| `Date` | Date on which the expense occurred |
| `Amount` | Amount spent |
| `Category` | Category of the expense |
| `Description` | Short description of the expense |

### Categories Used

- Food
- Transport
- Utilities
- Entertainment

---

## 🚀 How to Run the Project

### Step 1: Install Required Libraries

```bash
pip install numpy pandas matplotlib seaborn
```

### Step 2: Open Jupyter Notebook

```bash
jupyter notebook
```

### Step 3: Open the Project

Open:

```text
Smart_Expense_Tracker.ipynb
```

### Step 4: Keep the Dataset in the Same Folder

Make sure these files are together:

```text
Smart_Expense_Tracker.ipynb
expenses.csv
```

### Step 5: Run the Notebook

Run all notebook cells from top to bottom.

---

## 📈 Data Visualizations

### 📊 1. Bar Chart
Shows the total amount spent in each category and helps identify the highest spending category.

### 📈 2. Line Graph
Shows spending trends over time and helps understand changes in expenses across different dates.

### 🥧 3. Pie Chart
Shows the percentage distribution of total expenses among different categories.

### 📉 4. Histogram
Shows the frequency distribution of expense amounts.

---

## 🔎 Filtering Functionality

The project provides a `filter_expenses()` method.

### Filter by Category

```python
tracker.filter_expenses({
    "category": "Food"
})
```

### Filter by Date Range

```python
tracker.filter_expenses({
    "start_date": "2026-01-01",
    "end_date": "2026-01-31"
})
```

### Filter by Amount Range

```python
tracker.filter_expenses({
    "min_amount": 300,
    "max_amount": 800
})
```

---

## 🔢 NumPy Integration

NumPy is used for numerical calculations such as:

- Sum
- Mean
- Maximum
- Minimum

Example:

```python
np.sum(amounts)
np.mean(amounts)
np.max(amounts)
np.min(amounts)
```

---

## 🐼 Pandas Integration

Pandas is used for:

- Reading CSV files
- Creating DataFrames
- Cleaning data
- Filtering records
- Grouping data
- Category-wise expense analysis
- Monthly analysis
- Data aggregation

---

## 🛡️ Error Handling

The application handles common invalid inputs such as:

- Invalid date
- Invalid amount
- Negative amount
- Invalid category
- Empty description
- Empty dataset
- Invalid filter conditions

This helps prevent the application from crashing during normal user interaction.

---

## 🌟 Advantages

- Easy to use
- Simple and organized
- Stores expense records
- Provides useful spending analysis
- Supports filtering
- Provides visual insights
- Uses real-world data
- Demonstrates multiple Python concepts
- Easy to maintain and extend

---

## 🔮 Future Enhancements

The project can be further improved by adding:

- User Login and Authentication
- Monthly Budget Management
- Budget Limit Alerts
- PDF Report Generation
- Excel Report Generation
- Expense Prediction using Machine Learning
- Web Dashboard
- Mobile Application
- Cloud Database
- Advanced Financial Analytics
- Recurring Expense Management

---

## ✅ Conclusion

The **Smart Expense Tracker Application** is a practical Python project designed to help users record, analyze, and understand their personal expenses.

The project combines Python programming fundamentals with **Object-Oriented Programming, NumPy, Pandas, Matplotlib, and Seaborn** to create a complete data-driven application.

It demonstrates how Python and data analysis techniques can be applied to solve a real-world financial management problem.

---

## 👩‍💻 Author

**Author by PRIYAL PATEL**

---

⭐ **Smart Expense Tracker Application — Python Project**
