
<div align="center">

# 🛍️ Customer Behavior Analysis

### A small project to understand customer shopping habits using Python, SQL and Power BI.

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="SQL">
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI">
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter Notebook">
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge" alt="Project status">
</p>

</div>

---

## 📌 About the Project

I made this project to understand customer shopping behavior and find useful information from shopping data. I used **Python** to clean and prepare the data, **SQL** to answer business questions, and **Power BI** to present the results in a dashboard.

This project helped me practise working with data and understand how data can be used to make better business decisions.

## 🎯 What I wanted to learn

- Clean and prepare data using Python.
- Find useful patterns in customer purchases.
- Write SQL queries to answer business questions.
- Compare customer groups, products and purchase trends.
- Present the results in a Power BI dashboard.

## 🧰 Tools I used

| Tool | How I used it |
|---|---|
| 🐍 Python | Cleaning and preparing the data |
| 📓 Jupyter Notebook | Writing and running Python code |
| 🗄️ MySQL | Storing the data and running SQL queries |
| 📊 Power BI | Creating the dashboard |
| 🧹 Pandas | Working with the dataset |
| 🔗 SQLAlchemy | Connecting Python to the database |

## 🔄 Project Workflow

1. **Load the data** – I loaded the shopping data into a Jupyter Notebook using Pandas.
2. **Clean the data** – I checked missing values, filled missing review ratings using the median for each category, and cleaned the column names.
3. **Prepare new columns** – I created age groups and converted purchase frequency into number of days.
4. **Store the data** – I connected Python to MySQL and uploaded the cleaned data to the `customer` table in the `customer_behavior` database.
5. **Analyse with SQL** – I wrote queries to answer different questions about customers, products and revenue.
6. **Show the results** – I used Power BI to present the analysis in a dashboard.

## 🔍 Questions I explored with SQL

Here are some of the questions I worked on:

1. How much revenue comes from each gender?
2. Which customers used a discount but still spent more than the average?
3. Which five products have the highest average review ratings?
4. What is the average purchase amount for Standard and Express shipping?
5. How do subscribers and non-subscribers compare?
6. Which five products have the highest discount rate?
7. How many customers are new, returning or loyal?
8. What are the top three purchased products in each category?
9. How many repeat buyers are subscribers and non-subscribers?
10. How much revenue comes from each age group?

## 📁 Files in This Project

| File | Description |
|---|---|
| `customer behavior analysis.ipynb` | Python notebook for data cleaning and preparation |
| `customer behavior analysis.sql` | SQL queries used for the analysis |
| `customer behavior dashboard.pbix` | Power BI dashboard file |
| `customer_shopping_behavior.csv` | Dataset used by the notebook (keep this file in the project folder) |

> **Note:** The CSV dataset was not included with the project files I received. Add it to the project folder before running the notebook, or change the file path in the notebook if it is stored somewhere else.

## ▶️ How to Run the Project

### 1. Get the files ready

Download or clone this project and keep the notebook, SQL file, Power BI file and dataset in one folder.

### 2. Install the Python packages

Open a terminal and run:

```bash
pip install pandas numpy pymysql sqlalchemy jupyter
```

### 3. Run the notebook

Open Jupyter Notebook and run `customer behavior analysis.ipynb` from top to bottom.

Make sure the dataset path is correct.

### 4. Set up MySQL

- Start your MySQL server.
- Create or use the `customer_behavior` database.
- Update the database connection details in the notebook.
- Run the notebook so the cleaned data is uploaded to the `customer` table.
- Open `customer behavior analysis.sql` in your SQL tool and run the queries.

### 5. Open the Power BI dashboard

Open `customer behavior dashboard.pbix` in Power BI Desktop to view the dashboard.

## 🔐 Important Note

Before sharing this project, remove any personal database username or password from the notebook. Use your own MySQL login details, or store them safely as environment variables. Never upload real passwords to GitHub.

## 💡 What I learned

While doing this project, I got practice in data cleaning, handling missing values, creating new columns, connecting Python with MySQL, writing SQL queries and presenting data in Power BI. I also got a better idea of how customer data can help a business understand its customers.

## 🙌 Thank You

Thanks for checking out my project! Feel free to explore the notebook, SQL queries and Power BI dashboard.
