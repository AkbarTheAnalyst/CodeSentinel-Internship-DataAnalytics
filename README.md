# Internship Tasks – Data Analytics (Code Sentinel)  

This repository contains my completed internship tasks under the **Code Sentinel Internship Program**. The goal of these tasks was to build hands-on skills in **Python, Pandas, Data Visualization, and Business Intelligence tools** by working with real-world datasets.  


## Tasks Completed  

### **Task 1 – Load and Explore Data**  
- Loaded the **Titanic dataset** (`titanic_data.csv`) using **Pandas**.  
- Explored dataset structure: number of rows, columns, data types, and summary statistics.  
- Identified missing values and initial data quality issues.  


### **Task 2 – Clean and Preprocess Data**  
- Handled missing values in key columns (`Age`, `Embarked`, `Cabin`).  
- Removed duplicate entries where necessary.  
- Converted categorical values into consistent formats.  
- Saved a **cleaned dataset** (`titanic_data_cleaned.csv`) for reproducibility.  


### **Task 3 – Visualize Key Insights**  
- Used **Matplotlib** and **Seaborn** to create visualizations:  
  - **Bar plots**: Survival counts by gender and passenger class.  
  - **Histograms**: Age distribution of passengers.  
  - **Pie charts**: Survivors vs. non-survivors.  
  - **Boxplots**: Relationship between fare and passenger class.  
- Key insights: higher survival among **females** and **1st-class passengers**.  


### **Task 4 – Analyze Sales Data Using Grouping**  
- Used the **Superstore dataset** (`superstore.csv`) to perform grouping and aggregation:  
  - **Total Sales by Region**  
  - **Average Profit by Category**  
  - **Order Count by Ship Mode**  
  - **Sales & Profit by Sub-Category**  
  - **Sales by Region and Category**  
- Applied **Pandas groupby + agg** for summarization.  
- Created multiple **Seaborn bar plots** for visualization:  
  - Regional sales comparison  
  - Average profit per category  
  - Order count by shipping mode  
  - Sales vs. profit across sub-categories  
  - Regional sales breakdown by category  

**Tools Used:** Pandas, Seaborn, Matplotlib  


### **Task 5 – Create an Interactive Dashboard**  
- Imported data into **Power BI**.  
- Designed an **interactive dashboard** featuring:  
  - **Slicers** (Quarter, Region, Category)  
  - **KPIs** (Total Sales, Avg Sales, Total Profit)  
  - **Dynamic charts** (bar, line, and pie charts)  
- Enabled **real-time filtering** for business-friendly analysis.  

**Tools Used:** Power BI  


## Key Learnings  
- Hands-on experience in **data cleaning, preprocessing, visualization, and grouping** using Python.  
- Practical knowledge of **business reporting** through **Power BI dashboards**.  
- Improved ability to make projects **structured, reproducible, and professional**.  


## 📂 Repository Structure  

```bash
├── Task_1_to_3/
│   ├── titanic_data.csv
│   ├── titanic_data_cleaned.csv
│   ├── task1_2_3.ipynb
│
├── Task_4/
│   ├── superstore.csv
│   ├── task4.ipynb
│
├── Task_5/
│   ├── sales_dashboard.pbix
│   └── screenshots/
│
└── README.md
```