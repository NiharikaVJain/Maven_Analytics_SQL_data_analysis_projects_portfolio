### ▶️ How to Run the Code
This guide walks you through how to set up and run the SQL analysis in this project using MySQL Workbench.

###📦 Step 1: Install MySQL & Workbench

If you haven’t already:

Download MySQL Server: https://dev.mysql.com/downloads/mysql/

Download MySQL Workbench: https://dev.mysql.com/downloads/workbench/

💡 You can also use other SQL tools like DBeaver or Azure Data Studio if you prefer.

### 🗃 Step 2: Import the Maven Movies Database

Open MySQL Workbench

Create a new schema (e.g., maven_movies)

Open the file:
create_mavenmovies.sql (found in the root of this repository)

Select your new schema and run the SQL script to create all 16 tables and insert the sample data.

✅ The database includes tables like customer, rental, inventory, film, payment, store, etc.

### 📂 Step 3: Run Analysis Queries

Open any SQL file from the /queries/ folder:

01_inventory_analysis.sql

02_customer_insights.sql

03_staff_performance.sql

04_rental_trends.sql

05_revenue_insights.sql

Select your database (e.g., maven_movies) from the SCHEMAS tab

Run each query block and inspect the results in the output panel

🔍 Each file is organized with clear headers and comments to help you understand what each query does.

## 🧭 Visual Setup Guide (Flowchart)
Here’s the setup as a simple 4-step visual flow. Would you like this as a PNG image for your GitHub README or project folder?

plaintext
Copy
Edit
+-------------------------+
| 1. Install MySQL &     |
|    MySQL Workbench     |
+-------------------------+
           ↓
+-------------------------+
| 2. Load create_         |
|    mavenmovies.sql      |
|    into MySQL Workbench |
+-------------------------+
           ↓
+-------------------------+
| 3. Open /queries/*.sql  |
|    Run and explore data |
+-------------------------+
           ↓
+-------------------------+
| 4. Export results or    |
|    visualize (optional) |
+-------------------------+


✅ Example Output to Generate:

1.Top 10 most rented films
2.Monthly rental trends (line graph)
3.Staff revenue leaderboard (bar chart)
4.Customer spending heatmap
