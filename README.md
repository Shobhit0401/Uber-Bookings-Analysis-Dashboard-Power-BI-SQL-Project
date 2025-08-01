# Uber-Bookings-Analysis-Dashboard-Power-BI-SQL-Project

A full-scale **Power BI dashboard project** analyzing Uber bookings using **SQL for data extraction** and **Power BI for data visualization**. This project simulates real-world reporting for a ride-hailing service, featuring ride patterns, vehicle performance, cancellations, revenue analysis, and ratings — all backed by dynamic and interactive visuals.

---

## 🗃️ Dataset & Tools Used

* **SQL Server** for querying booking data
* **Power BI** for dashboard development
* **Excel/CSV** for data preprocessing

---

## 📁 Files Included

| File                  | Description                                      |
| --------------------- | ------------------------------------------------ |
| `uber_data.sql`       | SQL queries used for data extraction             |
| `Uber_Dashboard.pbix` | Power BI dashboard file                          |
| `README.md`           | Project overview                                 |
| `Booking_Data.xlsx`   | Base dataset (bookings, vehicles, ratings, etc.) |

---

## 🧠 Dashboard Pages Overview

1️⃣ **Overall Booking Summary**

This page gives a high-level summary of total bookings and booking value. It includes:

* **Booking status breakdown** through a pie chart (e.g. success, cancelled by driver, incomplete, etc.)
* **KPI indicators** displaying total bookings and total booking value
* **Ride volume over time** visualized with a line chart
* **Date slicer** to dynamically filter the visuals

This gives stakeholders a quick understanding of daily activity and booking outcomes.

2️⃣ **Vehicle Type Analysis**

This page explores ride trends and operational metrics by vehicle type:

* **Tables and cards** showing metrics like total distance traveled, average distance per ride, and revenue generated by each vehicle category
* Helps in understanding which vehicle types contribute most to operations

3️⃣ **Revenue Breakdown**

Dedicated to tracking Uber’s revenue performance:

* **Bar charts** for daily revenue and revenue by payment mode
* **Pie chart** comparing weekday vs weekend performance
* **Table listing top 5 customers** by booking value

Gives strong insights into customer lifetime value and preferred transaction methods.

4️⃣ **Cancellation Analysis**

This page dives into cancellation patterns:

* **Pie charts** breaking down cancellations by customer and driver with reason categories
* **KPI cards** showing cancellation rate and success rate

Useful to identify areas where user experience or driver engagement may need improvement.

5️⃣ **Ratings Overview**

This page evaluates service quality using customer and driver feedback:

* **Matrix visuals** comparing average customer ratings and driver ratings per vehicle type

Helps understand satisfaction trends and pinpoint segments with low service scores.

---

🔍 SQL Analysis Performed

Before building the dashboard in Power BI, comprehensive data analysis and preparation was done in **SQL**, including:

* Filtering data by date ranges to support time-series analysis
* Aggregating booking values, distances, and ratings by dimensions like vehicle type, date, and user ID
* Segregating booking statuses to calculate successful rides vs cancellations
* Ranking top customers based on spending
* Creating daily revenue summaries and cancellation summaries

The data extracted via SQL served as the foundation for Power BI's visual reporting and DAX-based calculations.

---

📊 Skills Demonstrated

* ✅ Data Modeling & Transformation
* ✅ DAX Calculations for KPIs
* ✅ Custom Visuals & Slicers in Power BI
* ✅ SQL Data Aggregation & Filtering
* ✅ Insightful Storytelling with Data

---

## 📌 Why This Project Stands Out

* Mirrors a **real business intelligence workflow**: from raw data → SQL extraction → Power BI modeling → dashboard delivery
* Covers **multiple business domains**: operations, customer service, revenue, and performance
* Designed with a clean, professional UX — aligned for business teams

---

## 🙋‍♂️ About Me

**Shobhit** | Data Analyst | Power BI & SQL Enthusiast
🔗 [LinkedIn](https://www.linkedin.com/in/shobhit6362)
![Screenshot 2025-07-26 at 01 27 14](https://github.com/user-attachments/assets/871fce1c-95b3-4f30-b0a9-bb93842d529a)


![Screenshot 2025-07-26 at 01 27 22](https://github.com/user-attachments/assets/e718a8ef-7eb7-42c6-bd92-f7ba04d7f8b2)

![Screenshot 2025-07-26 at 01 27 29](https://github.com/user-attachments/assets/faa99923-561e-4bfb-a442-2581f4e5258a)
![Screenshot 2025-07-26 at 01 27 35](https://github.com/user-attachments/assets/ab1a6f28-3ebe-4213-a8db-87affa7237bf)
![Screenshot 2025-07-26 at 01 27 42](https://github.com/user-attachments/assets/f6428c16-cd79-48e2-8085-7e857ad56068)
