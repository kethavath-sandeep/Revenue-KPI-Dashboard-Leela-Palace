

# Revenue KPI Dashboard for "The Leela Palace" 


![The Leela Palace-](https://github.com/kethavath-sandeep/Revenue-KPI-Dashboard-Leela-Palace/blob/main/the%20leela%20palace.jpg?raw=true)


## Problem Statement  
This dashboard was designed to help **The Leela Palace** hotel chain monitor and analyze their revenue streams and operational performance. The goal was to identify revenue sources, track trends, and provide actionable insights for data-driven decision-making. The dashboard highlights:  
- Key revenue drivers (e.g., room bookings, dining).  
- Seasonal trends and performance across departments.  
- Areas for improvement, like low-occupancy rates and underperforming services.  

By using this dashboard, **The Leela Palace** can enhance resource allocation, optimize pricing strategies, and improve overall operational efficiency.



## Steps Followed  

- **Step 1**: Data was collected from **The Leela Palace** in Excel and CSV formats, containing transactional data, customer demographics, and revenue details from March–May 2024.  
- **Step 2**: Data cleaning was performed using **Power Query**:  
   - Removed duplicates.  
   - Standardized date formats.  
   - Handled missing values and anomalies.  
- **Step 3**: Data modeling was done in **Power BI**:  
   - Relationships were created between tables (e.g., customer data, revenue).  
   - Calculated columns and measures were created using **DAX** to derive KPIs like total revenue and occupancy rates.  
- **Step 4**: Interactive dashboard design using **Power BI** included:  
   - **Key Metrics**: Total revenue, average spend, and occupancy rates.  
   - **Filters**: Parameters for city, department, and time period.  
   - **Visualizations**: Bar charts, line graphs, and tables for clear insights.  
   - **Drill-Downs**: Capability to analyze specific areas, such as month-over-month growth.  
- **Step 5**: The dashboard was tested to ensure accuracy and usability.  
- **Step 6**: The final dashboard was presented to stakeholders for review and feedback.  



## KPIs and Visuals Used  

1. Key Performance Indicators:  
   - Total Revenue (overall and departmental).  
   - Occupancy Rate.  
   - Total Successful Booking.
   - Average Rating.
   - Total Cancelled Booking.
   - Cancelation Rate.  

2. Filters and Interactive Elements:  
   - Time Periods: Weekly, monthly, and quarterly views.  
   - Departments: Rooms, dining, events, etc.  
   - Locations: Performance across hotel properties.  

3. Visualizations:  
   - **Bar Charts**: Revenue by departments and locations.  
   - **Line Graphs**: Revenue trends and seasonal variations.  
   - **Pie Charts**: Contribution of different revenue sources.
   - **Column Chart**: shows the percentage of rooms occupied by weekend and weekday.  

4. Calculated Columns and Measures:  

 **Total Revenue**  
`SUM([Revenue])`  
![Total Revenue](https://github.com/kethavath-sandeep/Revenue-KPI-Dashboard-Leela-Palace/blob/main/Total%20Revenue.png?raw=true)  

**Occupancy Rate**  
`SUM([Occupied Rooms])/SUM([Total Rooms])*100`  
![Occupancy Rate](https://github.com/kethavath-sandeep/Revenue-KPI-Dashboard-Leela-Palace/blob/main/Occupancy%20rate.png?raw=true)  

**Total Successful Booking**  
`Total Bookings = COUNT(fact_bookingss[booking_id])`  
![Successful Booking](https://github.com/kethavath-sandeep/Revenue-KPI-Dashboard-Leela-Palace/blob/main/Successful%20booking.png?raw=true)  

**Cancellation Percent**  
`DIVIDE([Total cancelled bookings],[Total Bookings])`  
![Cancellation Rate](https://github.com/kethavath-sandeep/Revenue-KPI-Dashboard-Leela-Palace/blob/main/Cancellation%20rate.png?raw=true)  

**Average Rating**  
`AVERAGE(fact_bookingss[ratings_given])`  
![Average Rating](https://github.com/kethavath-sandeep/Revenue-KPI-Dashboard-Leela-Palace/blob/main/Average%20rating.png?raw=true)  



# Snapshot of Dashboard (Power BI Service)

![Snapshot of Dashboard (Power BI Service)-](https://raw.githubusercontent.com/kethavath-sandeep/Revenue-KPI-Dashboard-Leela-Palace/refs/heads/main/dashboard%20.jpg)


# Report Snapshot (Power BI DESKTOP)

![Report Snapshot (Power BI DESKTOP)-](https://raw.githubusercontent.com/kethavath-sandeep/Revenue-KPI-Dashboard-Leela-Palace/refs/heads/main/KPI%20report.jpg)


### **Dashboard Link**: [https://app.powerbi.com/groups/473efd0b-c684-401b-adf6-a00221595bc3/reports/db51f7e0-be1d-47df-9e55-2c5a1290e10e?ctid=a6de9407-2d24-407d-81e6-941b053c301a&pbi_source=linkShare]  



## Insights  

The following are some important business insights derived from the revenue dashboard:
Mumbai generates highest revenue and Delhi the least revenue during March to May2024. Company need to focus on increasing the revenue in Delhi.
The occupancy rate is higher during weekends across all cities, months and booking platforms. Leverage this insight to increase revenue generated during weekends.
70% of the bookings are checked out while 5% of booking don’t show up across all cities and booking platforms which means 75% of bookings generate revenue for The Leela Palace hotels. 
Identify and analyze the reasons for cancellations and try to reduce them.
Avg rating varies between 3.4 to 3.8 across cities. Compare it with the industry benchmark across cities and evaluate the performance.
Occupancy rate is highest at Delhi with 60+ % for all months though generates least revenue compared to other cities. Identify the reason for higher occupancy and use that to drive the revenue growth.



## Challenges Faced  
1. **Data Inconsistencies**: Handled missing values, duplicates, and formatting issues.  
2. **Learning Curve**: Gained expertise in **DAX** and advanced Power BI functionalities.  
3. **Stakeholder Feedback**: Iterative reviews were required to meet stakeholder expectations.  



## Tools and Techniques Used  
- **Power BI**: Data visualization and dashboard development.  
- **Power Query**: Data cleaning and transformation.  
- **DAX**: Creating calculated columns and measures.  
- **Microsoft Excel**: Initial data cleaning and exploration.  
- **PowerPoint**: Presentation of the final dashboard to stakeholders.  



## Conclusion  
The KPI dashboard provided **The Leela Palace** with valuable insights into their business performance. It enabled the management team to:  
- Identify top-performing revenue streams and areas for improvement.  
- Optimize resource allocation and pricing strategies.  
- Make data-driven decisions to improve profitability and operational efficiency.  

