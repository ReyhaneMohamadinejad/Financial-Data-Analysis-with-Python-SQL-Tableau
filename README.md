# Financial-Data-Analysis-with-Python-SQL-Tableau

📌 Overview
This project focuses on financial data analysis using a combination of Excel, Python, SQL Server, and Tableau. The process involves:

Cleaning the raw data in Excel.
Loading the cleaned data into SQL Server using Python.
Extracting the data in Tableau and creating interactive dashboards.

🛠️ Tools & Technologies Used
📂 Excel → Data cleaning and preprocessing
🐍 Python (Pandas + pyodbc) → Loading data into SQL Server
🗄️ SQL Server → Storing and managing data
📊 Tableau → Data visualization and dashboard creation


🔄 Project Workflow
1️⃣ Data Cleaning in Excel
Removed duplicates and inconsistent values
Applied TRIM functions to clean text fields
Converted financial columns into proper numeric formats
2️⃣ Loading Data into SQL Server (Python)
Read the cleaned data from Excel using Pandas
Connected to SQL Server using pyodbc
Created the FinancialData table (if not already existing)
Deleted old records and inserted new clean data

3️⃣ Data Visualization in Tableau
Connected Tableau to SQL Server and extracted data
Created interactive visualizations, including:
✅ Monthly Revenue Trend (Line Chart)
✅ Cost and Profits Analysis (Bar Chart)
✅ The amount of Profit per Quarter (Bar Chart)
✅ Profit Margin (Trend Over Time) (Line Chart)
✅ Category Wise Analysis (Profit Margin by Category)


📊 Tableau Dashboard Features
The interactive dashboard allows users to filter data based on:
✔ Month
✔ Product Category
✔ Region
✔ Revenue

These visualizations help in identifying key insights and making data-driven business decisions.


📁 How to Run the Project
💾 1. Load Data into SQL Server (Python Script)
Place the Financial_Data_Dirty.xlsx file in the specified directory.

Run the command to load data into SQL Server.
python script.py

📊 2. Connect Tableau to SQL Server
Open Tableau and navigate to Connect → Microsoft SQL Server.
Enter the server name and database credentials.
Select the FinancialData table and start analyzing!

🚀 Key Takeaways
🔹 Data cleaning improves accuracy in financial reports.
🔹 SQL Server ensures efficient data storage and retrieval.
🔹 Tableau provides powerful visual analytics for decision-making.
🔹 Python automates data processing, making workflows more efficient.
