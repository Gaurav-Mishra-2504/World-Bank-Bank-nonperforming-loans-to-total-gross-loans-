# 🌍 World Bank NPL Analysis Dashboard

An end-to-end data analytics project transforming raw World Bank data into an interactive dashboard using **Excel Power Query** and **Power BI**.

---

## 🚀 Project Overview

World Bank datasets are highly authoritative but come in a **wide format** (years as columns), which is not suitable for dashboards.

This project demonstrates:
- Data cleaning & transformation  
- Converting wide data → long format  
- Building a relational data model  
- Creating KPIs using DAX  
- Designing an interactive dashboard  

📊 **Focus Metric:** Non-Performing Loans (% of total gross loans)

---

## 📂 Dataset

Source: **World Bank Open Data**

Files used:
- `API_FB.AST.NPER.ZS...` → Main dataset (NPL % by country & year)  
- `Metadata_Country...` → Country metadata (Region, Income Group)

---

## 🧹 Data Cleaning (Power Query)

Steps performed:

- Removed top junk rows  
- Promoted headers  
- Used **Unpivot Other Columns**  
- Converted data into long format  
- Removed null values  

✅ Final structure:
- Country Name  
- Country Code  
- Year  
- NPL Percentage  

---

## 🔗 Data Modeling (Power BI)

Created a **Star Schema**:

- **Fact Table:** NPL Data  
- **Dimension Table:** Country Metadata  

Relationship:
```
Country Code → Country Code
```

🎯 Enables:
- Region-wise filtering  
- Income group analysis  
- Clean data relationships  

---

## 📐 DAX Measures

### 📊 Average Global NPL
Calculates average loan risk across selected filters

### 📈 Max NPL (Peak Crisis)
Identifies highest NPL spike

### 🔄 Year-over-Year Change
Tracks increase/decrease in NPL over time

---

## 📊 Dashboard Features

- 📈 Time trend analysis (Line chart)  
- 🌍 Region-wise comparison  
- 💰 Income group insights  
- 🔢 KPI cards  

---

## 🛠 Tools & Skills

- Excel (Power Query)  
- Power BI  
- Data Cleaning  
- Data Modeling  
- DAX  
- Data Visualization  

---

## 📌 How to Run

1. Download data from World Bank  
2. Clean using Power Query  
3. Load into Power BI  
4. Create relationships  
5. Add DAX measures  
6. Build dashboard  

---

## 💡 Future Improvements

- Forecasting models  
- Real-time data integration  
- Automated refresh  
- Cloud deployment  

---

