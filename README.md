
# 🍕 Pizza Sales Data Analysis

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-purple)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Status](https://img.shields.io/badge/Project-Completed-success)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📊 Project Overview

This project performs a comprehensive exploratory and business analysis of a pizza sales dataset using **Python** and **Jupyter Notebook**.
The objective is to transform raw transactional data into meaningful operational and strategic insights through structured data cleaning, relational joins, and analytical modelling.

The project simulates a real-world retail analytics workflow, focusing on:

* Sales performance evaluation
* Customer ordering behaviour
* Menu engineering analysis
* Time-series trend exploration

---

## 🎯 Business Questions Answered

* What is the total revenue generated?
* How many pizzas were sold?
* What are the peak sales hours?
* Which weekday generates the most sales?
* What are the top 5 bestselling pizzas?
* What monthly trends are visible?
* Which pizzas are underperforming?

---

## 🧾 Dataset Structure

The project integrates four relational tables:

| Table             | Description                    |
| ----------------- | ------------------------------ |
| **pizza_types**   | Names, categories, ingredients |
| **pizzas**        | Sizes and prices               |
| **order_details** | Quantity per order             |
| **orders**        | Date and time of transactions  |

### 🔗 Relationship Flow

```
pizza_types → pizzas → order_details → orders
```

---

## ⚙️ Data Processing Pipeline

### ✔ Data Integration

* Merged relational tables using foreign keys
* Created a unified analysis-ready dataset

### ✔ Data Cleaning

* Converted data types
* Handled inconsistencies
* Standardised time and date formats

### ✔ Feature Engineering

* Combined date and time into timestamp
* Extracted hour, weekday, month
* Calculated revenue column

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook

---

## 📈 Example Visual Outputs

*(Replace image paths after exporting charts from your notebook)*

### Sales by Hour

```
![Sales by Hour](images/sales_by_hour.png)
```

### Sales by Weekday

```
![Sales by Weekday](images/sales_by_weekday.png)
```

### Monthly Sales Trend

```
![Monthly Sales](images/monthly_trend.png)
```

---

## 📂 Project Structure

```
pizza-sales-analysis/
│
├── 3. Samuel_Johnson.ipynb
├── dataset/
│   ├── pizzas.csv
│   ├── pizza_types.csv
│   ├── order_details.csv
│   └── orders.csv
│
├── images/
│   ├── sales_by_hour.png
│   ├── sales_by_weekday.png
│   └── monthly_trend.png
│
└── README.md
```

---

## 🚀 How to Run the Project

### 1️⃣ Clone Repository

```
git clone https://github.com/yourusername/pizza-sales-analysis.git
```

### 2️⃣ Install Dependencies

```
pip install pandas numpy matplotlib jupyter
```

### 3️⃣ Launch Notebook

```
jupyter notebook
```

### 4️⃣ Run Notebook Sequentially

Execute all cells from top to bottom.

---

## 📊 Key Analytical Insights

* Identification of peak customer ordering hours
* Weekly and monthly revenue patterns
* High-performing vs low-performing menu items
* Customer demand trends
* Operational workload forecasting

---

## 💼 Skills Demonstrated

* Data Cleaning & Preprocessing
* Exploratory Data Analysis (EDA)
* Relational Data Modelling
* Time-Series Analysis
* Business Intelligence
* Data Visualization
* Analytical Storytelling

---

## 🧠 Project Significance

This project demonstrates a realistic end-to-end data analytics workflow, suitable for:

* Data analyst portfolios
* Technical interviews
* Business analytics case studies
* Data science training exercises

---

## 👤 Author

**Samuel Johnson**
TechCrush Data Science Program – Task 3

---

## 📄 License

This project is licensed under the MIT License.

---

## ⭐ Future Improvements

* Predictive sales forecasting
* Dashboard development (Power BI / Tableau)
* Menu optimisation model
* Customer segmentation analysis

---

## 🔗 Connect

If you find this project useful, consider ⭐ starring the repository.


Say the word and I’ll produce that version 👍.
