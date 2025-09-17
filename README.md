# Blinkit-Sales-Analysis --- Power-BI-Dashboard
End-to-end Power BI project analyzing Blinkit’s sales data — includes data cleaning, modeling, DAX measures, and an interactive dashboard with insights on product categories, outlet sizes, locations, and customer satisfaction.

# Project Objectives: 
This Power BI project provides an in-depth analysis of Blinkit’s sales performance by examining revenue, sales growth, customer satisfaction, and outlet distribution. It highlights top-performing product categories, customer preferences, and outlet-level trends while uncovering opportunities to optimize product offerings and strengthen retention strategies. By consolidating critical KPIs into an interactive dashboard, the project delivers actionable insights that support data-driven decision-making, operational efficiency, and long-term business growth.

## Dataset Used

# 📌 Project Requirements  

## 🔹 Key Performance Indicators (KPIs)  

- **Total Sales** → Overall revenue generated from all transactions  
- **Average Sales** → Average revenue per transaction  
- **Number of Items** → Total quantity of items sold  
- **Average Rating** → Mean customer satisfaction score  
## 🔹 Business & Visualization Requirements  

1. **Sales by Fat Content**  
   - Objective: Assess the impact of fat content on overall sales and related KPIs  
   - Visualization: **Donut Chart**
       
2. **Sales by Item Type**  
   - Objective: Compare revenue contribution across different product categories  
   - Visualization: **Bar Chart**
     
3. **Fat Content by Outlet**  
   - Objective: Analyze outlet-level sales segmented by fat content  
   - Visualization: **Stacked Column Chart**
     
4. **Sales by Outlet Establishment**  
   - Objective: Evaluate how the age/year of outlets influences sales performance  
   - Visualization: **Line Chart**  

5. **Sales by Outlet Size**  
   - Objective: Identify the correlation between outlet size (Small/Medium/Large) and sales  
   - Visualization: **Donut / Pie Chart**  

6. **Sales by Outlet Location**  
   - Objective: Examine geographic sales distribution across Tier 1, Tier 2, and Tier 3 locations  
   - Visualization: **Funnel Chart**  

7. **KPIs by Outlet Type**  
   - Objective: Provide a consolidated view of all KPIs (Total Sales, Average Sales, Number of Items, Average Rating) across outlet types  
   - Visualization: **Matrix Table**
 ## 🔄 Process  

1. **Requirement Gathering** → Defined business KPIs & visualization needs.  
2. **Data Cleaning & Transformation** → Used **Power Query** to remove duplicates, fix missing values, and standardize formats.  
3. **Data Modeling** → Designed a **Star Schema** for efficient analysis (Fact: Sales, Dimensions: Products & Outlets).  
4. **DAX Calculations** → Built measures for **Total Sales, Avg Sales, Items Sold, and Avg Rating**.  
5. **Dashboard Development** → Designed interactive, business-focused visuals.  
6. **Insights & Recommendations** → Validated findings and derived business opportunities.

## 📈 Dashboard Highlights  

The dashboard provides a **360° view of business performance**:  
- 🔹 **KPI Cards** → Quick snapshot of Total Sales, Avg Sales, Items Sold, and Ratings  
- 🔹 **Category Analysis** → Top-performing item types driving revenue growth  
- 🔹 **Outlet Analysis** → Sales trends segmented by outlet size, type, and age  
- 🔹 **Customer Insights** → Ratings distribution highlighting satisfaction levels  
- 🔹 **Geographic View** → Funnel chart showing city-tier level contribution  
