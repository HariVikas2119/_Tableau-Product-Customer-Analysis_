# Tableau-Portfolio-Customer-Analysis-Practice-Project-
This repository contains a Tableau workbook created as a **practice project** using a publicly available dataset.   The analysis replicates a model/dashboard seen online for learning purposes.
---

## 📊 Project: Customer Year-over-Year Analysis
- **File**: [Skill] 
- **Tools Used**: Tableau
- **Practice Scope**:
  - Built using dataset available online (not proprietary data).
  - Dashboard design and metrics replicated from a reference model online.
  - Exercise intended for skill-building and showcasing Tableau capabilities.

---

## 🔍 Key Metrics & Calculations
The following techniques and calculations were practiced in this project:

- **Date Functions**
  - Extracting Current Year (CY) and Previous Year (PY) using `YEAR([Order Date])`
  - Filtering data dynamically based on `TODAY()`

- **Level of Detail (LOD) Expressions**
  - Distinct customer counts using `COUNTD([Customer ID])`
  - Conditional LOD expressions for CY and PY segmentation

- **Comparative Analysis**
  - CY Customers vs PY Customers
  - % Difference in Customers → `(CY - PY) / PY`

- **Dashboard Design**
  - KPIs for CY, PY, and % Difference
  - Clean layout for year-over-year customer insights
  - Interactive filters for year/date selection

- **Best Practices**
  - Using calculated fields instead of hardcoded years
  - Formatting measures as percentages for growth metrics
  - Keeping workbook reusable with dynamic date logic

---

## 🚀 How to Use
1. Download the `.twbx` file.  
2. Open in Tableau Desktop or Tableau Public.  
3. Explore dashboards interactively.  

---

## 📢 Disclaimer
This project is a **practice/learning exercise** and does not represent original business data.  

