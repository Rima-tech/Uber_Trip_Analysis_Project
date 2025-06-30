![Uber Logo](https://github.com/Rima-tech/Uber_Trip_Analysis_Project/blob/49bd8c64b5f99e6146eac059818803ae08d6908e/Uber_logo.png)
# 🚖 Uber Trip Analysis – Power BI Dashboard


## 📈 Business Objective

This project aims to analyze Uber trip data from **June 2024** to uncover insights into booking trends, location-based demand, time-based trends, Vehile preference and operational performance. The dashboard supports data-driven decisions in **fleet planning, pricing strategies, and resource allocation**.


## 🗃️ Dataset Overview

- **Source:** Keggle 
- **Total Tables Used:** 2  
  1. **Trip Detail Table**  
     - Columns: Trip ID, Pickup Time, Drop Off Time, passenger_count, trip_distance, PULocationID, DOLocationID, fare_amount, Surge Fee, Vehicle, Payment_type
  2. **Location Table**  
     - Columns: LocationID, Location, City
- **Time Period Covered:** June 1 – June 30, 2024
  ---

# 📄 Dashboard Pages


## 📍 1. Overview Analysis

![Overview Page](https://github.com/Rima-tech/Uber_Trip_Analysis_Project/blob/49bd8c64b5f99e6146eac059818803ae08d6908e/Uber_Overview%20Page.png)
![Overview Page](https://github.com/Rima-tech/Uber_Trip_Analysis_Project/blob/9fe8a1fa23e7db5f901f4ed4147c4b2d6724ebbe/uber_overview.mp4)


### 🔑 Key Elements:

- **KPIs Displayed:**
  1. **Total Bookings** – Total number of trips completed during the period
  2. **Total Booking Value** – Sum of revenue generated from all bookings
  3. **Average Booking Value** – Revenue earned per trip on average
  4. **Total Trip Distance** – Combined distance traveled across all trips
  5. **Average Trip Distance** – Average distance per trip
  6. **Average Trip Time** – Mean duration of trips in minutes

- **Charts & Tables:**
  - Bookings by Payment Type (e.g., Uber Pay, Cash)
  - Trip Type Distribution (Day vs Night)
  - Vehicle Type Analysis Table with metrics
  - Total Bookings by Day
  - Most Frequent Pickup & Drop Locations
  - Top 5 Location By total Bookings

- **Filters/Slicers:**
  - City
  - Date Range


### 💼 Business Implication
This page gives a clear summary of Uber’s operations during the selected period. It helps the business understand:

How many rides were taken and how much revenue was earned

What types of vehicles and payment methods are most used

Whether most trips happen during the day or night

Which locations have the highest pickup and drop activity

These insights can help Uber make better decisions about where to send more drivers, which services to promote, and how to improve customer experience.



## ⏱️ 2. Time Analysis

![Time Analysis Page](https://github.com/Rima-tech/Uber_Trip_Analysis_Project/blob/49bd8c64b5f99e6146eac059818803ae08d6908e/Uber_Time_Analysis.png)

### 🔑 Key Elements:
- **Visuals:**
  - Hourly Distribution of Bookings
  - Weekly Trend Line
  - Hour-by-Day Heatmap
- **Filters:** Pickup Date, Trip Type

### 💼 Business Implication:
This page helps the business understand when people are booking rides the most. It shows how demand changes by the hour of the day and day of the week, along with a heatmap that clearly highlights peak periods.

By looking at these patterns, the team can make smarter decisions about driver availability, staffing during busy times, and even promotions or pricing during low-demand hours. It’s a practical way to match supply with demand and improve service during the times customers need it most.


## 📊 3. Detail Page

![Detail Page](https://github.com/Rima-tech/Uber_Trip_Analysis_Project/blob/49bd8c64b5f99e6146eac059818803ae08d6908e/Uber_Detail_page.png)

### 🔑 Key Elements:
- **Trip Table:** Pickup Date ,Pickup Time, Location, Vehicle, Distance, Fare.
- **Drillthrough Enabled:** Navigate from high-level visuals to trip-specific data

### 💼 Business Implication:
This page gives a detailed, trip-by-trip view of the data. It allows users to drill down and see exactly what’s happening in each ride — including when and where it happened, how far the trip was, how much it cost, and what vehicle and payment type were used.

This kind of granular visibility helps the business verify trends seen on summary pages, spot unusual trips, and get a clearer picture of customer behavior and operational details. It’s especially useful for deeper analysis, audits, or decision-making based on real data.




## 🧠 Concepts & Features Used

- DAX Measures for custom KPIs
- Drillthrough Navigation
- Date/Time Intelligence
- Filters and bookmarks for interactivity


## 🛠️ Tools & Technologies

- Power BI Desktop (Latest Version)



