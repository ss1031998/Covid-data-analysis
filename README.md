# Covid-data-analysis
he purpose of the project is to help find out what the status update of COVID-19 is in all states of India using a dashboard that helps to organize the data.

**Steps to Create a COVID-19 Dashboard in Tableau
1. Data Collection & Preparation
Download a reliable dataset (CSV, Excel) containing COVID-19 case statistics (cases, deaths, recoveries, etc.).
Ensure the dataset has relevant fields like State, Date, Confirmed Cases, Recovered, Deaths, Active Cases.
Clean the dataset using Excel or Python (pandas) if necessary.

3. Connect Data to Tableau
Open Tableau Desktop.
Click on “Connect” → “Text File” (for CSV) or “Microsoft Excel”.
Load the COVID-19 dataset into Tableau.
4. Data Exploration & Relationships
Verify the data by checking field names, data types, and missing values.
Create calculated fields if necessary (e.g., Active Cases = Confirmed - (Recovered + Deaths)).
Ensure proper relationships (Joins/Blends) if multiple data sources are used.
5. Building Key Visualizations
(i) Map Visualization for Statewise COVID Cases
Drag State onto the Tableau Canvas.
Drag Confirmed Cases to Color and Size.
Choose “Filled Map” to show the impact visually.
(ii) Line Chart for Trend Analysis
Drag Date to Columns and Confirmed Cases to Rows.
Add filters for State-wise Analysis.
Format the chart for clarity.
(iii) Bar Chart for Statewise Comparison
Drag State to Rows and Confirmed Cases to Columns.
Sort the states in descending order.
Apply color gradients for better readability.
(iv) KPI Cards for Key Metrics
Create separate KPI cards for Total Cases, Recovered, Deaths, Active Cases.
Use SUM() functions and format numbers appropriately.
6. Creating the Dashboard
Click on New Dashboard.
Drag all the created visualizations into the dashboard.
Add Filters for State selection.
Enhance with Title, Legends, Tooltips, and Color Coding.
7. Publishing to Tableau Public
Click on Server → Tableau Public → Save to Tableau Public.
Upload the dashboard with an appropriate name and description.
Your Tableau Public link:
COVID-19 India Statewise Analysis
