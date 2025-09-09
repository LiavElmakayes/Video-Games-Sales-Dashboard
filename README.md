# 🎮 Video Games Sales Dashboard

Dashboard built with Power BI to analyze global video game sales from 1980 to 2020.  
The dashboard allows users to explore sales trends across genres, years, regions, publishers, and platforms.

---

## 🛠️ Tools Used
- **Power BI Desktop**  
- **Dataset:** Video Game Sales (Kaggle)  
- Optional: Python / SQL for preprocessing (if applicable)

---

## 📄 Dashboard Overview

### **Page 1 – Filters**
- **Year Slicer:** Filter data between 1980-2020  
- **Genre Slicer:** Filter by game genre  
> All other pages sync with these slicers, allowing interactive filtering across the dashboard.

### **Page 2 – KPI Cards**
Displays key metrics for a quick overview:
1. **Sum of Global Sales** – Total worldwide sales  
2. **Average of Global Sales** – Average sales per game  
3. **Count of Publishers** – Number of unique publishers  
4. **Count of Platforms** – Number of unique gaming platforms

### **Page 3 – Visuals**
1. **Global Sales Over Time (Line Chart)** – Shows worldwide sales trends across years  
2. **Sales by Genre and Region (Stacked Bar Chart)** – Compares sales per genre and per region (NA, EU, JP, Other)

### **Page 4 – Top 10 Games**
- **Table** displaying: Platform, Name, and Sum of Global Sales  
- Shows the top-selling 10 games globally

### **Page 5 – Heatmap: Genre vs Year**
- **Matrix Visual** with:  
  - **Rows:** Year  
  - **Columns:** Genre  
  - **Values:** Sum of Global Sales  
- Highlights trends of popular genres over time

---

## 🔍 Key Insights
- Action and Sports are the most popular genres globally  
- Top-selling games dominated by Wii Sports
- Sales peaked between 2002-2011  

---

## 🚀 How to Open
1. Clone this repository  
2. Open `VideoGamesDashboard.pbix` in Power BI Desktop
