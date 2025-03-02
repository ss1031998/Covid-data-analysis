# COVID-19 Dashboard in Tableau

## 🏥 Overview
This project demonstrates the **step-by-step process** of creating a **COVID-19 dashboard** in Tableau using real-world data. The dashboard provides insights into **state-wise COVID-19 cases, trends, comparisons, and key metrics**.

---

## 📌 Steps to Create a COVID-19 Dashboard

### 🔹 1. Data Collection & Preparation
- 📥 **Download** a reliable dataset (**CSV, Excel**) containing **COVID-19 case statistics** (_cases, deaths, recoveries, etc._).
- ✅ Ensure the dataset has relevant fields like **State, Date, Confirmed Cases, Recovered, Deaths, Active Cases**.
- 🛠️ **Clean the dataset** using **Excel** or **Python (pandas)** if necessary.

### 🔹 2. Connect Data to Tableau
- 🖥️ **Open** **Tableau Desktop**.
- 🔗 Click on **Connect** → **Text File** _(for CSV)_ or **Microsoft Excel**.
- 📊 **Load** the COVID-19 dataset into Tableau.

### 🔹 3. Data Exploration & Relationships
- 🔍 **Verify** the data by checking **field names, data types, and missing values**.
- ➕ **Create calculated fields** if necessary:  
  ```diff
  Active Cases = Confirmed - (Recovered + Deaths)
  ```
- 🔗 **Ensure proper relationships** (_Joins/Blends_) if multiple data sources are used.

---

## 📊 Building Key Visualizations

### 🗺️ (i) Map Visualization for Statewise COVID Cases
- 🌍 **Drag State** onto the Tableau Canvas.
- 🎨 **Drag Confirmed Cases** to **Color** and **Size**.
- 🏙️ Choose **Filled Map** to show the impact visually.

### 📈 (ii) Line Chart for Trend Analysis
- 📅 **Drag Date** to **Columns** and **Confirmed Cases** to **Rows**.
- 🎯 **Add filters** for **State-wise Analysis**.
- 🎨 **Format the chart** for clarity.

### 📊 (iii) Bar Chart for Statewise Comparison
- 📍 **Drag State** to **Rows** and **Confirmed Cases** to **Columns**.
- 🔢 **Sort the states** in **descending order**.
- 🌈 **Apply color gradients** for better readability.

### 🔢 (iv) KPI Cards for Key Metrics
- 📌 **Create separate KPI cards** for **Total Cases, Recovered, Deaths, Active Cases**.
- 🧮 Use **SUM() functions** and **format numbers appropriately**.

---

## 🚀 Publishing to Tableau Public
- 🌍 Click on **Server** → **Tableau Public** → **Save to Tableau Public**.

---

## 📌 Tableau Public Link
🔗 Check out the published dashboard here:  
👉 **[COVID-19 India Statewise Analysis](https://public.tableau.com/app/profile/subham.sinha/viz/covid19indiaanalysisstatewise/covid19indiastatewiseanalysis)**

---

## 👨‍💻 Author
🔹 **Subham Sinha**  
🔗 **LinkedIn:** [Profile](https://www.linkedin.com/in/saisubhamsinha/)  
🔗 **GitHub:** [Profile](https://github.com/ss1031998)

