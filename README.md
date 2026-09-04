# 🚖 Uber Trip Analysis Dashboard

## 📌 Overview
This repository showcases a **multi-layered Power BI dashboard** analyzing Uber trip data for June 2024.  
The dashboard provides insights into bookings, revenue, trip distances, payment types, vehicle categories, and location trends.  

---

## 📊 Dashboard Pages
![Overview Dashboard](https://github.com/Amit-DataDoc23/Uber-Trip-Analytics-Dashboard/blob/8f72697210c50db7dcea0df0cc6d0b5c0bfd1727/Overview_Dashboard.png)

### 1. Overview
- High-level KPIs (bookings, revenue, avg. trip metrics)  
- Payment type distribution (Uber Pay, Cash, Amazon Pay, Google Pay)  
- Trip type analysis (Morning, Day, Evening, Night)  
- Vehicle type breakdown (UberX, Comfort, Black, XL, Green)  
- Location insights (frequent pickup/drop-off points, farthest trip)  
---

### 2. Time Analysis
![Time Analysis Dashboard](https://github.com/Amit-DataDoc23/Uber-Trip-Analytics-Dashboard/blob/8f72697210c50db7dcea0df0cc6d0b5c0bfd1727/Time_Analysis_Dashboard.png)

- Bookings by day and hourly slots  
- Weekly booking distribution (Mon–Sun trends)  
- Peak vs off-peak travel insights  
---

### 3. Detail Grid
![Detail Grid Dashboard](https://github.com/Amit-DataDoc23/Uber-Trip-Analytics-Dashboard/blob/8f72697210c50db7dcea0df0cc6d0b5c0bfd1727/Detail_Grid.png)
- Trip-level detail with fields:  
  - Trip ID, Pickup Date, Vehicle, Payment Type, Passenger Count  
  - Trip Distance, Booking Value  
  - Pickup & Drop-off Locations  
---

### Key Features
- **Layered Pages**:  
  - Overview  
  - Time Analysis  
  - Detail Grid  
- **Dynamic Elements**:  
  - Dynamic parameters  
  - Dynamic titles  
  - Interactive slicers  
 - **KPIs**:  
  - Total Bookings: 103.73K  
  - Total Booking Value: $1.55M  
  - Avg. Booking Value: $14.98  
  - Total Trip Distance: 349K miles  
  - Avg. Trip Time: 15.86 minutes
--- 

## 📈 Insights
- **UberX dominates** with ~38K bookings and $583K revenue.  
- **Penn Station/Madison Sq West** is the most frequent pickup point.  
- **Upper East Side North** is the most frequent drop-off point.  
- Longest trip: **Lower East Side → Crown Heights North (144.1 miles)**.  
- Evening trips contribute the highest booking value.  
---

## 🛠️ Tech Stack
- **Power BI Desktop**  
- **Data Source**: Uber trip dataset (June 2024)  
- **DAX Measures**: CALCULATE, USERELATIONSHIP, VAR, SUM, DIVIDE  
- **Dynamic Features**: Parameters, titles, slicers  

---

## 👨‍💻 Author
**Amit Mohan Srivastav**

## 📚 Source & Inspiration
Dataset & design inspired by **SkillCourse**
