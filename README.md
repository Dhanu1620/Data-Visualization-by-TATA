📊 Online Retail Sales Dashboard — Tata Group Case Study (Power BI)

Objective: Deliver actionable business insights to the CEO and CMO of a retail company based on 2011 sales data using Power BI.

---

🧠 Context
This project was developed as part of a simulated business challenge by Tata Group. The dataset included thousands of rows of online retail transactions from 2011. My role was to serve as a Data Analyst and present insights visually to support executive decisions.

---

📂 Dataset Overview
Fields: InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country

Challenges: Missing values, negative values, lack of time-based hierarchy

Solution: Filter, clean, and enhance data using Power Query & DAX formulas

---

⚙️ Tools & Techniques Used
Power BI Desktop

Power Query Editor

DAX (Data Analysis Expressions)

Custom Columns:

TotalRevenue = Quantity * UnitPrice

MonthYear = FORMAT([InvoiceDate], "MMM YYYY")

MonthSort = FORMAT([InvoiceDate], "YYYYMM") (used to sort MonthYear chronologically)

---

📌 Business Questions Answered
✅ Q1: Monthly Revenue Trends (CEO)
Visual: Line Chart

Insight: Revenue spikes during Q4 (Oct–Dec), showing strong seasonality.

✅ Q2: Top 10 Revenue Countries (Excluding UK) (CMO)
Visual: Bar Chart

Insight: Germany, Netherlands, France top the list. Good candidates for international focus.

✅ Q3: Top 10 Customers by Revenue
Visual: Descending Bar Chart

Insight: A few customers contribute significantly to revenue — an opportunity for loyalty programs or personalized promotions.

✅ Q4: Country-wise Quantity Demand (Excluding UK)
Visual: Heatmap/Bar Chart

Insight: Quantity sold is spread across multiple countries; optimize global supply chain planning.

---

📊 Visual Summary
All dashboards are created using best practices:

Sorted by MonthSort for correct chronological display

Filters applied in visuals to maintain clean, segmented views

Aggregated using SUM() for Quantity and TotalRevenue

---

🎬 Final Output

Explained data cleaning, modeling, and dashboard insights

Contextualized each visual with business strategy relevance

---

📈 What I Learned
Time intelligence in Power BI using DAX

How to build dynamic visuals for business storytelling

Applying filters, grouping, and custom sort orders

Structuring insights for executive presentation

---

🚀 Future Enhancements
Add drill-through pages for individual country analysis

Forecasting future revenue using Power BI’s built-in forecasting tools

Embed Power BI report to web
