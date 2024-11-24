# 💡*Electricity Usage Analysis* 💡

Morocco Electricity Consumption (Electricity Usage Analysis) – Writeup 

### **The Situation:** You’ve been hired as a Demand Analyst for Morocco’s National Power Co.
### **The Assignment:** Morocco’s National Power Co. is assessing plans for upgrading its infrastructure.

#### You’ve been asked to analyze seasonality in electricity consumption, to help identify peak lead periods across hours of the day and days of the week to help make investments to prevent outages during these times. 

#### 💡Objectives: 
1.	Prepare the data for analysis
2.	Prepare data & visualize seasonal patterns w a line chart
3.	Pivot the data by date parts to visualize seasonality with a heatmap

---

💡Objective #1 – Prepare the data for analysis

The first objective is to read in the relevant columns from the dataset and create new calculated columns for analysis. 

-	Read in 4 columns from the _powerconsumption.csv_ file and cast the field 'Datetime' as a datetime datatype.
-	Create a _'total_consumption'_ column which represents the **sum** of the three 'PowerConsumption' columns.
-	Create two columns by extracting the dateparts from the 'Datetime' column.
---
💡Objective #2 - Visualize consumption over time

The second objective is to build a stacked line chart visualizing the power consumption for the month of January 2017.

-	Resample the data into **1 hour** increments.
-	Filter the data down to the month of January 2017.
-	Create a stacked line chart using the _'PowerConsumption'_ columns.
---
💡Objective #3 - Visualize consumption seasonality

The final objective is to build a heatmap for the average power consumption by day of week & hour of day and report any interesting findings.

-	Create a pivot table where the rows are day of week, the columns are the hour of day, and the values represent the average total consumption.
-	Create a heatmap using the pivot table.
-	What trends or patterns do you notice in power consumption?
-	Challenge: Instead of integers, use the names for each day of the week.
---
