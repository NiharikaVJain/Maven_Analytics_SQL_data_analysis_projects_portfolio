# Maven_Analytics_SQL_data_analysis_projects_portfolio

## Table of Contents

-[Overview: Role](https://github.com/NiharikaVJain/Maven_Analytics_SQL_data_analysis_projects_portfolio/blob/main/README.md#-role-data-analyst-business-owner-simulation) 

-[Overview: Project Scope](https://github.com/NiharikaVJain/Maven_Analytics_SQL_data_analysis_projects_portfolio/blob/main/README.md#-project-scope) 

-[Data Sources](https://github.com/NiharikaVJain/Maven_Analytics_SQL_data_analysis_projects_portfolio/blob/main/README.md#-data-source)

-[Entity Relationship Diagram (ERD)]

-[Tools and Technologies](https://github.com/NiharikaVJain/Maven_Analytics_SQL_data_analysis_projects_portfolio/blob/main/README.md#-tools--technologies)

-[Key Concepts and Skills](https://github.com/NiharikaVJain/Maven_Analytics_SQL_data_analysis_projects_portfolio/blob/main/README.md#-key-concepts--skills-demonstrated)

-[Sample Insights uncovered](https://github.com/NiharikaVJain/Maven_Analytics_SQL_data_analysis_projects_portfolio/blob/main/README.md#-sample-insights-uncovered)

## 🎬 Maven Movies — SQL Data Analysis Project

### 📍 Role: Data Analyst (Business Owner Simulation)

In this project, I stepped into the role of a business owner who had just acquired **Maven Movies**, a traditional DVD rental store. I aimed to explore the business using SQL to uncover insights into **inventory management**, **staff performance**, and **customer behavior**.

---

### 🧩 Project Scope

- **Objective**: Analyze business operations and performance metrics using SQL
- **Database**: 16 interrelated tables including rentals, inventory, payments, and customers
- **Tools Used**: MySQL, MySQL Workbench

---

### 💾 Data Source

- **Database Name**: `create_mavenmovies`
- **Content**: Includes 16 tables on customers, films, inventory, payments, rentals, staff, and stores
- **Setup**: Imported and analyzed using MySQL Workbench
- [Maven Analytics – Maven Movies Dataset](https://www.mavenanalytics.io/data-playground?page=2&dataset=maven-movies)

---
### 🗂️ Entity Relationship Diagram (ERD)
The ER Diagram provides a visual representation of the database schema used in the Maven Movies project. It helps in understanding how different tables are related to each other and supports effective query planning and data analysis.

Key Tables:

customer, rental, payment – represent the transactional flow of rentals and payments.

film, category, inventory – detail the movie catalog and stock.

store, staff – define the organizational structure.

actor, film_actor – represent many-to-many relationships between actors and films.

The ERD makes it easier to:

Identify foreign key relationships

Understand one-to-many and many-to-many links

Build efficient SQL joins across the schema

📌 Refer to the diagram below to visualize the database structure used for SQL queries:



---

### 🛠 Tools & Technologies

- **SQL (MySQL)** – Core querying and data manipulation
- **MySQL Workbench** – IDE for database exploration and analysis

---

### 🧠 What I Did
I began with foundational SQL queries—selecting, filtering, and aggregating data—to familiarize myself with the database. I then advanced into more complex scenarios involving multi-table joins, subqueries, and data transformation techniques to solve practical business problems.

---

### 🧠 Key Concepts & Skills Demonstrated

- SQL querying fundamentals: `SELECT`, `WHERE`, `GROUP BY`, `ORDER BY`, `HAVING`
- Advanced joins: `INNER`, `LEFT`, `RIGHT`
- Subqueries and Common Table Expressions (CTEs)
- Conditional logic: `CASE`, `IF`, `COUNT`
- Data transformation with UNION operator
- Bridging unrelated tables using intermediate joins
- Business insight generation from raw relational data

---

### 📊 Sample Insights Uncovered

| Insight Area            | Description                                                                 |
|-------------------------|-----------------------------------------------------------------------------|
| 🎞️ Film Performance     | Identified top and bottom rented films by category and rating              |
| 👥 Customer Behavior     | Segmented customers based on rental frequency and total spending           |
| 👨‍💼 Staff Performance    | Analyzed staff transactions to determine top performers                    |
| 📅 Rental Trends         | Discovered peak rental periods by day and month                            |
| 🧾 Revenue & Payments    | Evaluated revenue by store, category, and customer demographics            |

---

