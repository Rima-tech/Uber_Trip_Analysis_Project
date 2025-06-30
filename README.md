
# 🚖 Uber Trip Analysis – Power BI Dashboard


## 📈 Business Objective

This project aims to analyze Uber trip data from **June 2024** to uncover insights into booking trends, location-based demand, time-based trends, Vehile preference and operational performance. The dashboard supports data-driven decisions in **fleet planning, pricing strategies, and resource allocation**.

---

## 🗃️ Dataset Overview

- **Source:** Keggle (Link - )
- **Total Tables Used:** 2  
  1. **Trip Detail Table**  
     - Columns: `Trip ID`, `Pickup Time`, `Drop Off Time`, `passenger_count`, `trip_distance`, `PULocationID`, `DOLocationID`, `fare_amount`, `Surge Fee`, `Vehicle`, `Payment_type`
  2. **Location Table**  
     - Columns: `LocationID`, `Location`, `City`
- **Time Period Covered:** June 1 – June 30, 2024

# 📄 Dashboard Pages

---

## 📍 1. Overview Analysis

![Overview Page](./screenshots/overview_page.png)
<!-- Or use a GIF if available: ![Overview Demo](./assets/overview_demo.gif) -->

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

- **Filters/Slicers:**
  - City
  - Date Range


### 💼 Business Relevance (Simplified)
This page gives a clear summary of Uber’s operations during the selected period. It helps the business understand:

How many rides were taken and how much revenue was earned

What types of vehicles and payment methods are most used

Whether most trips happen during the day or night

Which locations have the highest pickup and drop activity

These insights can help Uber make better decisions about where to send more drivers, which services to promote, and how to improve customer experience.



## ⏱️ 2. Time Analysis

![Time Analysis Page](./screenshots/time_analysis_page.png)

### 🔑 Key Elements:
- **Visuals:**
  - Hourly Distribution of Bookings
  - Weekly Trend Line
  - Hour-by-Day Heatmap
- **Filters:** Pickup Date, Trip Type

### 💼 Business Relevance:
Helps identify **peak demand hours and days**, aiding in workforce planning, dynamic pricing, and service availability forecasting.

---

## 📊 3. Detail Page

![Detail Page](./screenshots/detail_page.png)

### 🔑 Key Elements:
- **Trip Table:** Pickup Time, Location, Vehicle, Distance, Fare, Payment Type
- **Drillthrough Enabled:** Navigate from high-level visuals to trip-specific data
- **Filters:** Pickup Date, Vehicle Type

### 💼 Business Relevance:
Provides granular visibility into each trip for validation, operational review, or segmentation analysis. Supports root-cause investigations and decision justification.

---

## 🧠 Concepts & Features Used

- DAX Measures for custom KPIs
- Drillthrough Navigation
- Date/Time Intelligence
- Slicers & Filters for interactivity
- Power Query for data cleaning

---

## 🛠️ Tools & Technologies

- Power BI Desktop (Latest Version)
- ScreenToGif / OBS Studio (for GIFs or screen recording)
- GitHub for Version Control and Hosting

---

## 🔗 [View Live Repository](https://github.com/your-username/uber-trip-analysis-powerbi)

---

