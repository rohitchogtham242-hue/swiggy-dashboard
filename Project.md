# 🍔 Swiggy Sales Insights Dashboard

## 📌 Project Overview
An interactive data analytics dashboard built to track and visualize Swiggy's food delivery performance across India. Analyzing **197,430 orders** across **28 states and cities** (covering **993 restaurants**) from **January 2025 to August 2025**, this project transforms raw transactional data into actionable business insights regarding revenue trends, customer preferences, regional performance, and dietary splits.

<img width="1067" height="516" alt="Screenshot 2026-11-16 204232" src="https://github.com/user-attachments/assets/ac1e3fc3-0f5e-45a6-bb50-49b05264b46b" />


## Dataset used
- <a href="https://github.com/mortes-tech/swiggy-dashboard/blob/main/Swiggy%20Raw%20Data%20Excel(1).xlsx">Dataset view</a>

---

## 📊 Key Performance Indicators (KPIs)
* **Total Sales Revenue:** ₹53,012,505.77 (~₹53.01 Million)
* **Total Orders:** 197,430
* **Average Order Value (AOV):** ₹268.51
* **Average Customer Rating:** 4.34 / 5.0
* **Total Customer Ratings Count:** 5,591,574

---

dashboard <a href="https://github.com/mortes-tech/swiggy-dashboard/blob/main/Screenshot%202026-11-16%20204232.png">dashboard view</a>

## 🔍 Key Business Insights

### 1. Dietary Preference Split (Veg vs. Non-Veg)
* **Vegetarian Orders:** Account for **64.48%** of total revenue (**₹34.18M** across 139,546 orders).
* **Non-Vegetarian Orders:** Account for **35.52%** of total revenue (**₹18.83M** across 57,884 orders).

### 2. Regional & City Performance
* **Top Performing State:** **Karnataka** leads all 28 states with **₹5.46M** in revenue, followed by **Uttar Pradesh** (₹3.12M), **Telangana** (₹3.02M), and **Maharashtra** (₹3.02M).
* **Top 5 Cities by Revenue:** 
  1. **Bengaluru:** ₹5,456,798.41
  2. **Lucknow:** ₹3,117,359.65
  3. **Hyderabad:** ₹3,021,711.62
  4. **Mumbai:** ₹3,015,573.35
  5. **New Delhi:** ₹2,829,180.60
  *(Together, these top 5 cities generate **₹17.44M**, representing ~32.9% of total sales).*

### 3. Temporal Trends (Monthly, Quarterly & Weekly)
* **Quarterly Breakdown:** **Q2** generated the highest sales at **₹19.90M** (74,163 orders), closely followed by **Q1** at **₹19.67M** (73,096 orders), and **Q3** (Jan–Aug partial data) at **₹13.44M** (50,171 orders).
* **Peak Months:** **January** (₹6.83M), **May** (₹6.79M), and **August** (₹6.79M) recorded the highest monthly revenues.
* **Day-of-Week Trends:** Sales remain consistent throughout the week, peaking on **Saturdays** (**₹7.78M**) and **Thursdays** (**₹7.66M**), with **Tuesdays** seeing the lowest volume (**₹7.36M**).

---

## 🛠️ Data Processing & Workbook Architecture
The project workbook is structured into dedicated analytical layers:
* **`Swiggy Data`:** Raw transactional dataset (197,430 records) enriched with calculated columns for **Day of Week**, **Quarter**, **Week Number**, and rule-based **Food Type classification** (`Veg` vs. `Non-Veg`) derived from dish names.
* **`Analysis`:** Pivot tables and `GETPIVOTDATA` formulas aggregating KPIs, monthly/weekly trends, quarterly performance, state/city rankings, and food-type splits.
* **`Dashboard`:** Interactive visual reporting layer featuring dynamic charts and slicers for multi-dimensional filtering.

---

## 🚀 How to Use
1. Download or open the workbook in Microsoft Excel or Google Sheets.
2. Navigate to the **`Dashboard`** tab to explore visual trends.
3. Use the interactive **Slicers** to filter metrics dynamically by State, City, Quarter, or Food Type.
