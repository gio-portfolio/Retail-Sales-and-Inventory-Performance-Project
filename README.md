# 🏪 Retail Sales & Inventory Performance Analysis

## 📋 Project Overview
This project explores **retail sales and inventory performance** using Excel and Power BI.  
The goal was to identify sales trends, regional performance differences, and inventory management issues to provide actionable business insights.

The analysis was completed in two stages:
1. **Excel:** Data cleaning, preparation, and pivot table analysis.  
2. **Power BI:** Dashboard creation and visualisation of key findings.

---

## ⚙️ Preparation Phase

### **Sales Table Creation**
- Cleaned and standardised the sales dataset for analysis.

### **Inventory Table Creation**
As the dataset did not include inventory data, a new inventory table was created from scratch using Excel formulas.  

**Process:**
- Used `Product ID` and `VLOOKUP` to fetch corresponding product names.  
- Created four key inventory metrics:
  - **Starting Stock:** `Sales * 1.5`
  - **Reorder Point:** `Starting Stock * (0.25 - 0.4)`
  - **Current Stock:** `Starting Stock - Sales`
  - **Reorder Needed:** `=IF([@[Current Stock]] < [@[Reorder Point]], "Yes", "No")`
- Introduced variability in the reorder point to simulate realistic stock requirements.  
- Final table contained **30 products**.

---

## 📊 Analysis & Insights

### **1️⃣ Product & Category Sales Performance**
**Findings:**
- **Top 3 Products:**  
  1. Canon imageCLASS 2200 Advanced Copier  
  2. Fellowes PB500 Electric Punch Binding Machine  
  3. Cisco TelePresence System EX90 Videoconferencing Unit  
- **Top 3 Sub-Categories:** Phones, Chairs, Storage  
- **Top Category:** Furniture  

**Insight:**  
Two of the top products were electric, with Phones leading sub-category sales.  
Chairs ranked second, driving strong Furniture sales.  

**Recommendation:**  
Focus marketing on **electronic and furniture-related products** to capitalise on customer demand.

---

### **2️⃣ Regional Performance**
**Findings:**
- South region **lags significantly** behind other regions in sales.  
- Furniture underperforms in the South, while **Technology** sells ~25% higher than other categories.  
- Machines rank #2 in South, replacing Storage (a top performer elsewhere).  

**Insight:**  
Weak Furniture sales reduce overall Southern performance, but Machines present an opportunity to strengthen Technology category growth.

**Recommendation:**  
- Focus promotions on **Technology (especially Machines)** to leverage South’s existing demand.  
- Re-evaluate Furniture strategy in the South (product mix, pricing, marketing).

---

### **3️⃣ Seasonality Trends**
**Findings:**  
Sales **peak in November, December, and September**, with the lowest activity in **January and February**.

**Insight:**  
High sales at year-end are likely driven by **holiday shopping demand**.

**Recommendation:**  
- Run **holiday promotions** and **bundle offers** during Q4.  
- Implement early-year incentives (January–February) to smooth seasonal dips.

---

### **4️⃣ Inventory & Stock Analysis**
**Findings:**
- 12 **Office Supplies**, 7 **Furniture**, and 3 **Technology** products are below reorder point.  
- Within Office Supplies, **Binders** account for 5 reorder alerts — the highest of any subcategory.  

**Insight:**  
Stockout risk is concentrated in **Office Supplies**, especially **Binders**, which are essential repeat-purchase items.  

**Recommendation:**  
- Prioritise replenishing Office Supplies to avoid stockouts.  
- Review reorder policies to ensure critical SKUs are restocked earlier.  

---

## 📈 Dashboards & Visualisations

### **Retail Sales Dashboard (Power BI)**
![Retail Sales Dashboard](Retail%20Sales%20Dashboard.png)

---

### **Regional Sales Performance (Excel Analysis)**
![Region Sales Performance ](Region%20Sales%20Performance.jpg)

---

### **Seasonal Sales Performance (Excel Analysis)**
![Season Sales Performance](Season%20Sales%20Performance.jpg)

---

### **Retail Inventory Dashboard (Power BI)**
![Retail Inventory Dashboard](Retail%20Inventory%20Dashboard.png)

---

### **Office Supplies Reorder Risk (Excel Analysis)**
![Office Supplies Reorder Risk](Office%20Supplies%20Reorder%20Risk.jpg)

---

## 🧠 Key Takeaways
- Technology and Furniture dominate sales performance.  
- The South region underperforms due to weak Furniture sales.  
- Peak demand occurs around holidays (Q4).  
- Office Supplies (Binders) represent the highest reorder priority.  
- Combining **sales and inventory analysis** provides actionable insights for both marketing and operations.

---

## 🧰 Tools Used
- **Excel** – Data cleaning, calculated columns, and pivot table analysis.  
- **Power BI** – Interactive dashboard creation and data visualisation.  

---

## 📂 Files in Repository
| File | Description |
|------|--------------|
| `Raw Superstore Data.xlsx` | Original uncleaned dataset. |
| `Superstore Retail Analysis.xlsx` | Cleaned and analysed Excel file containing sales and inventory analysis. |
| `Superstore Dashboard.pbix` | Power BI dashboard file combining sales and inventory analysis. |
| `Retail Sales Dashboard.png` | Power BI sales performance dashboard image. |
| `Retail Inventory Dashboard.png` | Power BI inventory performance dashboard image. |
| `Region Sales Performance.jpg` | Regional sales performance visual. |
| `Season Sales Performance.jpg` | Seasonal sales trend visual. |
| `Office Supplies Reorder Risk.jpg` | Inventory risk visual focusing on Office Supplies. |
| `README.md` | Project documentation (this file). |

---

## 🧩 Project Summary
This project demonstrates an end-to-end retail data workflow:  
**Data Cleaning → Analysis (Excel) → Visualisation (Power BI) → Business Insights & Recommendations.**  
It showcases analytical thinking, business storytelling, and technical proficiency in Excel and Power BI.

---

*Created by [Giovanni Ellis] — Data Analyst Portfolio Project (2025)*  
