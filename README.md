# Customer Shopping Behaviour

## 📌 Project Overview

This project delivers a comprehensive analysis of retail consumer behavior, designed to translate raw data into actionable strategic business intelligence. I developed an end-to-end data analytics workflow that identifies purchase drivers, customer segmentation, and loyalty trends to optimize marketing and product strategies.

**Key Achievements:**
* ✅ **Data Architecture & Cleaning (Python):** Engineered a robust data pipeline using Python to clean, transform, and prepare raw retail data for high-level analysis.
* ✅ **Strategic Analysis (SQL):** Developed complex SQL queries to extract deep insights regarding customer spending habits, frequency, and demographic segmentation.
* ✅ **Visual Storytelling (Power BI):** Designed an interactive, executive-level dashboard to visualize key performance indicators (KPIs) and trends, enabling data-driven decision-making.
* ✅ **Business Impact:** Formulated clear, evidence-based recommendations to improve customer engagement and sales performance.

---

## 🛠️ Project Workflow & Usage

### 1. Clone the Repository
```bash
git clone [https://github.com/mukuldhattarwal/Customer-Shopping-Behaviour.git](https://github.com/mukuldhattarwal/Customer-Shopping-Behaviour.git)
cd Customer-Shopping-Behaviour
```
### 2. Data Processing (Python)
I used the Jupyter Notebook `customer shopping behaviour.ipynb` to handle the initial data ingestion and cleaning.
* **Process:** The notebook imports the raw `customer_shopping_behavior.csv`, performs exploratory data analysis (EDA), and preprocesses the data for the database.
* **Action:** Run the notebook to generate the clean dataset and establish the connection to the SQL server.

### 3. Database Analysis (SQL)
The `pgsql.sql` script contains the analytical core of the project.
* **Database Setup:** Initializes the schema and tables required for the analysis.
* **Insights:** Execute the queries within this file to reproduce my analysis on customer segments and purchasing patterns.

### 4. Interactive Dashboard (Power BI)
Open `Customer Behaviour Dashboard.pbix` to interact with the visualizations.
* **Features:** The dashboard connects to the processed data to display dynamic views of sales trends, customer demographics, and category performance.
* ## 📂 Repository Structure

| File Name | Description |
| :--- | :--- |
| `customer shopping behaviour.ipynb` | Python source code for EDA, data cleaning, and ETL pipeline. |
| `pgsql.sql` | SQL script containing schema creation and analytical queries. |
| `Customer Behaviour Dashboard.pbix` | Power BI dashboard file for data visualization. |
| `customer_shopping_behavior.csv` | Original dataset used for this project. |
