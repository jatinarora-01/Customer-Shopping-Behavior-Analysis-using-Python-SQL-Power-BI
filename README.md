# 🛍️ Customer Shopping Behavior Analysis | Python, MySQL & Power BI

## 📌 Project Overview

This project demonstrates an end-to-end data analytics workflow focused on analyzing customer shopping behavior and extracting actionable business insights from retail customer data.

The project covers data preparation and exploratory analysis using **Python**, business-oriented data querying using **MySQL**, and interactive data visualization using **Power BI**. It follows a practical analytics workflow designed to demonstrate skills relevant to Data Analyst, Business Analyst, and Product Analytics roles.

The objective is to transform raw customer shopping data into meaningful insights that can support data-driven business decisions.

## 🎯 Project Objectives

- **Data Preparation:** Import, inspect, clean, and prepare raw customer shopping data for analysis using Python.
- **Exploratory Data Analysis (EDA):** Understand the dataset, examine customer characteristics, and explore shopping behavior patterns.
- **SQL Analysis:** Use MySQL queries to investigate business questions related to customers, purchases, customer segments, and shopping trends.
- **Data Visualization:** Develop an interactive Power BI dashboard to present important metrics, patterns, and trends.
- **Business Insights:** Interpret analytical findings and identify potential opportunities for improving customer understanding and business performance.

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| Python | Data preparation, cleaning, and exploratory analysis |
| MySQL | Database management and SQL-based business analysis |
| Power BI | Interactive dashboards and data visualization |
| Jupyter Notebook | Executing and documenting the Python analysis |
| SQL | Querying data and answering business questions |

## 🔄 Project Workflow

The project follows a structured analytics pipeline:

1. **Data Import:** Load the raw customer shopping dataset into Python.
2. **Data Cleaning and Preparation:** Inspect data quality, handle data preparation requirements, and organize the dataset for analysis.
3. **Exploratory Data Analysis:** Examine the dataset to understand customer attributes and purchasing behavior.
4. **MySQL Integration:** Load the prepared data into a MySQL database for structured querying.
5. **SQL Business Analysis:** Write SQL queries to investigate customer behavior and answer relevant business questions.
6. **Power BI Dashboard:** Connect Power BI to the MySQL data source and create visualizations to communicate analytical findings.
7. **Insights and Reporting:** Summarize the findings and identify potential business implications.

## 📊 Key Areas of Analysis

The analysis focuses on exploring customer shopping behavior and answering business-oriented questions, including:

- **Customer Segmentation:** Explore customer groups and differences in shopping behavior.
- **Purchasing Patterns:** Analyze purchase-related data to identify trends and patterns.
- **Customer Loyalty:** Investigate available indicators of customer loyalty and repeat purchasing behavior.
- **Shopping Trends:** Examine relevant customer and transaction attributes to understand purchasing patterns.
- **Business Intelligence:** Present analytical findings through visualizations that support informed decision-making.

*The specific metrics, dimensions, and conclusions depend on the dataset and the analyses implemented in the project.*

## 🐍 Python Analysis

Python is used for preparing the dataset and conducting exploratory data analysis.

The Python workflow covers:

- Importing the dataset and required libraries.
- Inspecting the dataset's structure and data types.
- Examining missing values, duplicates, and data quality.
- Cleaning and transforming data as required.
- Exploring customer and purchase-related attributes.
- Preparing the data for loading into MySQL.

## 🗄️ MySQL Analysis

MySQL is used to store and query the prepared customer shopping data.

The SQL analysis focuses on translating business questions into structured queries and extracting relevant information from the dataset.

The workflow includes:

- Creating and selecting a MySQL database.
- Loading the prepared dataset into the database.
- Writing SQL queries to investigate customer shopping behavior.
- Analyzing relevant customer segments and purchase patterns.
- Preparing query results for reporting and visualization.

## 📈 Power BI Dashboard

Power BI is used to transform the analytical data into an interactive visual reporting experience.

The dashboard is intended to help users explore customer shopping behavior and understand patterns in the data.

The visualization workflow includes:

- Connecting Power BI to the MySQL database.
- Importing the relevant data for reporting.
- Organizing data for visualization.
- Creating charts and dashboard elements based on the analysis.
- Presenting customer and purchasing insights in an accessible format.

*Refer to the Power BI project file for the actual dashboard pages, visuals, and metrics implemented.*

## ⚙️ Getting Started

Follow these steps to set up and explore the project locally.

### Prerequisites

Install or configure the following tools:

- Python 3
- Jupyter Notebook or JupyterLab
- MySQL Server
- MySQL Workbench or another MySQL client
- Power BI Desktop

### 1. Clone the Repository

```bash
git clone https://github.com/jatinarora-01/Customer-Shopping-Behavior-Analysis-using-Python-SQL-Power-BI.git
cd Customer-Shopping-Behavior-Analysis-using-Python-SQL-Power-BI
```

Replace the placeholders with your actual GitHub repository URL and repository name.

### 2. Set Up Python

Create and activate a virtual environment if desired.

**Windows:**

```bash
python -m venv .venv
.venv\Scripts\activate
```

Install the Python libraries required by your notebook:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

Install any additional packages imported by your notebook.

### 3. Run the Python Notebook

Open Jupyter Notebook:

```bash
jupyter notebook
```

Open the project notebook and execute the cells in order to inspect, clean, and prepare the dataset.

Ensure that the dataset is available at the path expected by the notebook.

### 4. Configure MySQL

1. Start your MySQL Server.
2. Create a database for the project.
3. Configure the database connection details in the Python notebook, if applicable.
4. Execute the notebook's database-loading steps to load the prepared data into MySQL.
5. Verify that the data has been loaded successfully.

Example database creation command:

```sql
CREATE DATABASE customer_behavior;
USE customer_behavior;
```

Use the actual database and table names defined in your implementation when running the project queries.

**Database connection note:** Configure your MySQL host, port, username, and password according to your local environment. Avoid committing passwords or other credentials to GitHub.

### 5. Execute the SQL Queries

Open the project's SQL file in MySQL Workbench or your preferred SQL editor.

Run the queries against the database and review the results for the business questions addressed by the project.

Ensure that the selected database and table names match those created during the data-loading step.

### 6. Open the Power BI Dashboard

1. Open the `.pbix` file in Power BI Desktop.
2. Configure the MySQL connection if prompted.
3. Update the server, database, or credentials as required by your environment.
4. Refresh the data and review the available dashboard visuals.

The exact connection and refresh steps depend on how the Power BI report was configured.

## 📁 Project Structure

A typical repository structure for this project may look like the following. Update the filenames to match the files included in your repository.

```text
customer-shopping-behavior-analysis/
│
├── data/
│   └── <dataset-file>
│
├── notebooks/
│   └── Customer_Shopping_Behavior_Analysis.ipynb
│
├── sql/
│   └── customer_behavior_sql_queries.sql
│
├── powerbi/
│   └── customer_behavior_dashboard.pbix
│
└── README.md
```

If your notebook, SQL file, dataset, and Power BI dashboard are stored in the repository root, reflect that structure instead.

## 💡 Business Value

This project demonstrates how multiple data analytics tools can work together to support business analysis:

- Python provides a workflow for preparing and exploring raw data.
- MySQL enables structured data storage and business-oriented querying.
- Power BI communicates findings through interactive visual reporting.
- Combining these tools creates a repeatable workflow for transforming raw data into useful business information.

## 🚀 Skills Demonstrated

- Data Cleaning and Preparation
- Exploratory Data Analysis (EDA)
- Python for Data Analytics
- SQL Querying and Business Analysis
- MySQL Database Integration
- Power BI Dashboard Development
- Data Visualization
- Analytical Thinking
- Translating Business Questions into Data Analysis

## 🔮 Potential Future Enhancements

- Add more advanced customer segmentation analysis.
- Explore additional purchasing and customer retention metrics.
- Improve dashboard interactivity and filtering.
- Automate parts of the data preparation and refresh workflow.
- Document key business findings with supporting charts and recommendations.

These are potential enhancements rather than claims about functionality already implemented.

## 🎥 Project Reference

This project was developed with reference to the following tutorial, with modifications including the use of MySQL as the database.

**YouTube Tutorial:** [Customer Shopping Behavior Analysis Project](https://www.youtube.com/watch?v=5PrZvPeUw60)

## 👨‍💻 About the Author

I am a Computer Engineering graduate interested in data analytics, business intelligence, and software development. I enjoy working with data to explore patterns, answer business questions, and communicate insights through analytical tools.

This project reflects my practical experience with Python, MySQL, and Power BI in an end-to-end data analytics workflow.

**Connect with me:**
- LinkedIn: `https://www.linkedin.com/in/jatinarora098/`
- GitHub: `https://github.com/jatinarora-01`

---

⭐ If you find this project useful, consider starring the repository.

