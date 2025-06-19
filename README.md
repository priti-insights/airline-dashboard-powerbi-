# airline-dashboard-powerbi-
Power BI project analyzing flight and ticket information.
# ✈️ Airline Dashboard - Power BI Project

A Power BI project that visualizes flight and ticket booking data using interactive visuals, DAX, drill-through, and slicers. This project is created as part of a data analysis assignment to explore and present airline performance insights.

---

## 📁 Project Overview

This dashboard provides insights into:

- Total number of passengers and flights per airline
- Ticket booking status distribution
- Best-performing flights vs. those needing improvement
- Destination-wise filtering
- Drill-through capability for airline-specific analysis
- Bookmarks to save different report views

---

## 📊 Visuals Created

- ✅ **Multi-card**: Shows number of passengers and flights for each airline  
- 📊 **Bar Chart**: Compares number of passengers per airline  
- 🍩 **Donut Chart**: Displays ticket booking statuses (Confirmed, Pending, Cancelled)  
- 🌳 **Decomposition Tree**: Breaks down flights by Airline and Destination  
- 🔎 **Q&A Visual**: Allows natural language search (e.g., “Show total tickets by status”)  
- 🎯 **Drill-through Page**: Enables drilling from Airline Overview to Destination Details  
- 📌 **Slicers**: Filter by Destination, Airline, Booking Status  
- 🔖 **Bookmarks**: Save different views of the report  

---

## 🧮 DAX Measures

- `Total Passengers on FL5011`
- `Total Tickets Booked`
- `BestFlightsTable` – filtered table for only best flights  
- Custom column to classify flights as “Best” or “To Be Improved”

---

## 🛠 Data Preparation

### Performed in Power Query:
- Removed duplicates and handled null values
- Standardized booking status (e.g., "On Time" → "On-Time")
- Created conditional columns to classify flight quality
- Used **Column from Examples** to extract flight number
- Merged Flight Information and Ticket Information using `FlightID`
- Created unique passenger ID using merged columns

---



## 🧠 Key Insights

- Airline A has the highest number of confirmed tickets
- Majority of ticket statuses are “Confirmed”
- Some flights have frequent delays and are flagged as “To Be Improved”
- Drill-through provides focused insights on each airline and its destinations

---

