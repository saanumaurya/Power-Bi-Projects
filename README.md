# 🚕 NCR Ride Analysis Dashboard (Power BI)

## 📘 Project Overview
This project analyzes **ride-hailing data across the National Capital Region (NCR)** to uncover insights about customer behavior, operational efficiency, revenue performance, and demand trends.  
The analysis is performed using **Power BI**, with interactive dashboards designed for business decision-making.

---

## 📊 Dataset Information

**File Name:** `ncr_ride_bookings.csv`  
**Total Records:** 150,000  
**Total Columns:** 21  
**Time Period:** Year 2024  
**Data Source:** Simulated operational data of an NCR-based ride-hailing service.

### 🧾 Column Descriptions

| Column | Description |
|--------|--------------|
| `Date` | Date of the booking |
| `Time` | Time of the booking |
| `Booking ID` | Unique identifier for each ride |
| `Booking Status` | Ride outcome (Completed, Cancelled, Incomplete, No Driver Found, etc.) |
| `Customer ID` | Unique customer reference |
| `Vehicle Type` | Type of vehicle (Bike, Auto, Sedan, eBike, etc.) |
| `Pickup Location` | Ride start location |
| `Drop Location` | Ride destination |
| `Avg VTAT` | Vehicle Time Arrival – time taken by driver to reach pickup |
| `Avg CTAT` | Customer Trip Arrival Time – duration of the ride |
| `Cancelled Rides by Customer` | Count/flag of customer cancellations |
| `Reason for Cancelling by Customer` | Reason provided by customer for cancellation |
| `Cancelled Rides by Driver` | Count/flag of driver cancellations |
| `Driver Cancellation Reason` | Reason for driver cancellation |
| `Incomplete Rides` | Indicates if a ride was not completed |
| `Incomplete Rides Reason` | Reason for incomplete rides |
| `Booking Value` | Total fare amount (in ₹) |
| `Ride Distance` | Distance traveled (in km) |
| `Driver Ratings` | Rating given by customer to driver (1–5 scale) |
| `Customer Rating` | Rating given by driver to customer |
| `Payment Method` | Mode of payment (UPI, Cash, Debit Card, etc.) |

---

## 🎯 Project Objectives

- Analyze **ride demand patterns** (hourly, daily, weekday vs weekend)
- Identify **peak demand hours** and **high-performing routes**
- Examine **revenue trends** by vehicle type and location
- Study **cancellation behavior** (customer vs driver)
- Evaluate **driver and customer satisfaction**
- Explore **payment method preferences**

---

## 📈 Power BI Dashboard Features

### **1. Executive Summary**
- KPIs: Total Rides, Completed Rides, Revenue, Avg Distance, Cancellation Rate, Avg Rating  
- Trends: Daily and Monthly booking overview  

### **2. Demand Insights**
- Hourly ride trends  
- Weekday vs Weekend demand comparison  
- Heatmap of rides by hour and day  

### **3. Cancellations & Issues**
- Cancellation reasons (Driver vs Customer)  
- Impact of VTAT/CTAT on cancellations  

### **4. Revenue & Payment Insights**
- Revenue by vehicle type  
- Average fare per km  
- Payment mode distribution  

### **5. Driver & Customer Analytics**
- Rating distributions  
- Top drivers by number of rides and rating  
- Repeat vs new customers  

---

## ⚙️ Technologies Used
- **Power BI Desktop** – Data visualization and dashboard creation  
- **DAX (Data Analysis Expressions)** – Calculations and KPIs  
- **Power Query Editor** – Data transformation and cleaning  
- **Microsoft Excel / CSV** – Dataset source  

---

##Screeshots/demos
eg: https://github.com/saanumaurya/Power-Bi-Projects/blob/main/snapshot%20ncr-ride-booking.png
