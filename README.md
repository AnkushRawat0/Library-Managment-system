# 📚 Library Management Analysis

## 🚀 Project Overview

This project analyzes library transaction data to understand user behavior, borrowing patterns, and return trends. The goal is to derive actionable insights that help improve inventory management, optimize book availability, and enhance return discipline.

The project simulates a real-world scenario where libraries track book usage and aim to improve operational efficiency through data-driven decisions.

---

## 🎯 Objectives

* Identify most borrowed books and popular categories
* Analyze borrowing duration patterns
* Evaluate late vs on-time return behavior
* Measure fine collection trends
* Provide business recommendations for optimization

---

## 🛠️ Tech Stack

* **Python** (Pandas, NumPy)
* **Data Visualization** (Matplotlib, Seaborn)
* **Jupyter Notebook**

---

## 📂 Project Structure

```
library-management-analysis/
│
├── data/                # Dataset (CSV file)
├── notebook/            # Jupyter notebooks
├── visuals/             # Graphs & charts
├── README.md            # Project documentation
```

---

## 📊 Dataset

* Synthetic dataset generated using Python
* ~1000+ library transactions
* Includes realistic business logic:

  * Borrow duration between 1–20 days
  * Late return logic with fine calculation
  * Multiple categories and book types

### 🔑 Key Columns:

* `transaction_id`
* `book_title`
* `category`
* `user_id`
* `issue_date`
* `return_date`
* `fine_amount`

---

## 🔍 Key Analysis Performed

### 1. Data Cleaning & Feature Engineering

* Converted date columns to datetime format
* Created `borrow_days` feature (return_date - issue_date)
* Identified late returns based on borrow duration

---

### 2. Exploratory Data Analysis (EDA)

* Total transactions
* Most borrowed books
* Category-wise popularity
* Average borrowing duration
* Late vs on-time returns
* Fine collection analysis

---

### 3. Borrow Duration Analysis

Analyzed distribution of how long users keep books:

* Identified common borrowing ranges
* Observed user return behavior patterns

---

### 4. Return Behavior Analysis

* Compared late vs on-time returns
* Evaluated return discipline among users

---

## 📈 Visualizations

* Top Borrowed Books (Bar Chart)
* Category Popularity (Bar Chart)
* Borrow Duration Distribution (Histogram)
* Late vs On-Time Returns (Bar Chart)

---

## 💡 Key Insights

* Machine Learning and DSA are the most borrowed books, indicating high demand for technical resources
* AI category has the highest usage, showing strong interest in emerging technologies
* Borrowing duration is mostly concentrated between 10–15 days
* On-time returns slightly exceed late returns, but the margin is minimal
* Close gap between late and on-time returns indicates potential risk of increasing delays

---

## 📌 Business Recommendations

* Increase inventory for high-demand books like Machine Learning and DSA
* Focus on expanding AI and Data Science resources
* Implement reminder systems to reduce late returns
* Optimize borrowing duration policies based on user behavior

---

## 🧠 Learning Outcomes

* Hands-on experience in end-to-end data analysis workflow
* Strong understanding of user behavior analysis
* Improved data visualization and storytelling skills
* Ability to derive actionable business insights from data

---

## 🚀 Future Improvements

* Build a recommendation system for books
* Predict late returns using machine learning
* Create an interactive dashboard (Power BI / Tableau)

---

## 👨‍💻 Author

**Ankush Rawat**
Aspiring Data Analyst | MERN Stack Developer transitioning into Data Science

---

## ⭐ If you like this project

Give it a ⭐ on GitHub and feel free to connect!
