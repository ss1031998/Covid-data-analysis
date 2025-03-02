COVID-19 India Statewise Analysis Dashboard
📌 Overview
This Tableau dashboard provides a statewise analysis of COVID-19 cases in India, offering insights into confirmed cases, recoveries, deaths, and trends over time.

🔗 Tableau Public Dashboard
🔗 View the Live Dashboard

📊 Features of the Dashboard
✅ Interactive Map: Visualizes the spread of COVID-19 across Indian states.
✅ Trend Analysis: Line chart showing case progression over time.
✅ Statewise Comparison: Bar chart highlighting top-affected states.
✅ KPI Metrics: Displays key COVID-19 statistics (Total Cases, Recoveries, Deaths, Active Cases).

📁 Dataset
The dataset contains COVID-19 case statistics for Indian states, including:

State
Date
Confirmed Cases
Recovered Cases
Deaths
Active Cases (Calculated: Confirmed - (Recovered + Deaths))
Data Source: Reliable COVID-19 data providers (e.g., government sources, Kaggle, JHU).

Format: CSV / Excel

🚀 Steps to Create This Dashboard
1️⃣ Data Collection & Preparation
Obtain the latest COVID-19 dataset (CSV/Excel).
Clean the data using Excel or Python (pandas) if needed.
2️⃣ Connect Data to Tableau
Open Tableau Desktop → Click "Connect" → Load CSV/Excel file.
3️⃣ Data Exploration & Relationships
Verify column names, data types, and missing values.
Create calculated fields (e.g., Active Cases = Confirmed - (Recovered + Deaths)).
4️⃣ Building Key Visualizations
✅ Map Visualization (Statewise COVID Cases)
Drag State onto the Tableau Canvas.
Drag Confirmed Cases to Color & Size → Choose "Filled Map".
📈 Line Chart (Trend Analysis)
Drag Date to Columns, Confirmed Cases to Rows → Add State filter.
📊 Bar Chart (Statewise Comparison)
Drag State to Rows, Confirmed Cases to Columns → Sort in descending order.
🔢 KPI Metrics (Total Cases, Recovered, Deaths, Active Cases)
Create separate KPI cards for key metrics.
5️⃣ Creating the Dashboard
Click New Dashboard → Add all visualizations.
Include Filters (State selection), Legends, Titles, & Tooltips.
6️⃣ Publishing to Tableau Public
Click "Server" → "Tableau Public" → "Save to Tableau Public".
Share the public Tableau link.

