# 🚕 Ola Bookings Analysis Dashboard (Power BI)

This project presents an interactive Power BI dashboard developed to analyze Ola ride bookings data. The dashboard provides insights into customer behavior, booking trends, cancellation reasons, and operational performance.

---

## 📊 Dashboard Highlights

The dashboard covers the following key metrics and visualizations:

### 1. **Booking Overview**
- Total number of bookings
- Total Booking Value
- Booking status breakdown (Success, Cancelled by Customer, Cancelled by Driver, Incomplete)
- Trends over time (Daily/Monthly booking trends)
![Overall](https://github.com/user-attachments/assets/058f047f-2a76-4b50-9935-3c0b7205e741)

### 2. **Cancellation Analysis**
- Top reasons for cancellations by customers and drivers
- Displayed key KPIs—including total bookings, successful rides, cancellations, and cancellation rate—to provide a 
  quick overview of service performance and operational efficiency.
![Cancellation](https://github.com/user-attachments/assets/3749bf71-ef2c-445a-9169-b4d7d4db6104)

### 3. **Vehicle Type Performance Analysis**
- Visualized total booking value, average distance, and total distance traveled across different vehicle types to identify high-performing categories.
- Enabled comparison of revenue and usage patterns between vehicle types, supporting data-driven decisions on fleet optimization.
- Highlighted customer preferences and operational load by vehicle class, aiding in targeted service improvements and pricing strategies.
![Vehicle Type](https://github.com/user-attachments/assets/18b58f55-ae96-4248-9df0-01ea77772a46)

### 4. **Revenue Based Analysis**
- Revenue by Payment Mode(Showing distribution of revenue from Card, Cash, Wallet, etc.).Useful for understanding customer payment preferences.
- Top 5 High-Value Customers: A ranked visual showcasing the top 5 customers based on total booking value. This insight helps identify 
  the most profitable users and supports targeted loyalty or reward strategies.
- Revenue Over Time:Time-series visual showing revenue trends daily, weekly,monthly or yearly.Helps detect seasonal spikes, dips, or promotions impact.
![Revenue](https://github.com/user-attachments/assets/7f0e6a61-d053-46aa-8af8-2ae0148090c0)


### 5. **Customer & Driver Insights**
- Average customer and driver ratings
- Ratings comparison across vehicle types
  ![Rating](https://github.com/user-attachments/assets/adbc123d-4057-4c1a-98b0-809a91e269cd)

---

## 🔍 Dataset

The dataset includes 100,000 records with the following key features:
- **Date & Time** of bookings
- **Booking ID**, status, and customer ID
- **Vehicle Type**, pickup and drop locations
- **Booking Value**, ride distance, and ratings
- **Cancellation Reasons**
- **Payment Modes**

---

## 📁 Files in This Repository

- `Ola_Bookings.csv` — Raw dataset
- `Ola_Dashboard.pbix` — Power BI dashboard file
- `README.md` — This file

---


## 💡 Tools Used
- Power BI (Data modeling, DAX, Visualization)
- Excel/CSV for data input
- Basic data cleaning inside Power BI

---

## 📌 Project Goal

This project simulates a real-world analysis scenario for a ride-hailing company to help improve operational efficiency and user satisfaction by deriving actionable insights from ride booking data.


