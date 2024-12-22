# **Global Super Store Dashboard**

### **Project Overview**
This Power BI project analyzes the Global Super Store dataset, consisting of 51,291 rows and 24 columns, to provide actionable insights into sales, profit, shipping, and customer trends. The dashboard is designed to support decision-making with interactive visualizations, Key Performance Indicators (KPIs), and dynamic filtering.

---

### **Features**
- **Data Transformation**:  
  - Processed and cleaned the dataset using Power Query for accuracy and consistency.  
  - Created a **Calendar Table** using DAX for time-based analysis.  

- **Dynamic Slicers**:  
  - Added slicers for Market, Region, Country, Category, Sub-category, Product Name, and Date (Year, Month, Day).  

- **Key Performance Indicators (KPIs)**:  
  - Total Sales, Total Profit, Total Orders, Return Rate, Average Delivery Days, Total Discounts, and Shipping Costs.  
  - Applied conditional formatting (red accent bars) for Return Rate and Total Returns.  

- **Advanced Visualizations**:  
  - Maps for Country, State, and City.  
  - Pie Charts for Sales by Segment, Shipment Mode, and Market.  
  - Line Charts for Sales and Profit trends over time.  
  - Bar Charts for Top 5 Products by Profit/Loss and Top 5 Customers by Profit.  
  - Drill-through pages for detailed performance analysis.  

- **Interactive Navigation**:  
  - Implemented a "View Sales & Performance" button for seamless page switching.  

---

### **Technical Details**
- **Tools Used**: Power BI, Power Query, DAX  
- **Dataset**: Global Super Store (51,291 rows, 24 columns)  
- **Visualization Types**: Map, Line Chart, Pie Chart, Bar Graph, Matrix Table, Clustered Column Chart  
- **Key Metrics**: Sales, Profit, Quantity, Discount, Shipping Cost, Return Rate, Delivery Time  

---

### **Repository Structure**
Global_Super_Store_Dashboard/
- │
- ├── Dataset/
- │   └── Global_Super_Store.xlsx               # Original dataset used in the project
- │
- ├── Screenshots/
- │   ├── Dashboard_Main_Page.png              # Screenshot of the main dashboard
- │   ├── KPI_Visualizations.png               # Screenshot of KPI visualizations
- │   ├── Sales_By_Region.png                  # Screenshot of sales by region
- │   └── Drill_Through_Page.png               # Screenshot of drill-through page
- │
- ├── Scripts/
- │   ├── Calendar_Table_DAX.txt               # DAX script for creating the Calendar table
- │   ├── KPI_Measures_DAX.txt                 # DAX scripts for KPIs like Total Returns, Return Rate, etc.
- │   └── Data_Cleaning_Steps.txt              # Steps and logic used for cleaning the dataset
- │
- ├── Global_Super_Store.pbix                  # Power BI file containing the dashboard
- │
- ├── LICENSE                                  # License file (e.g., MIT License)
- │
- └── README.md                                # Documentation file for the repository

