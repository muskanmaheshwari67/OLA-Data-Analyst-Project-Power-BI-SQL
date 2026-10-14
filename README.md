# OLA-Data-Analyst-Project-Power-BI-SQL
The OLA Data Analyst Project analyzes ride-booking data using SQL and Power BI to track ride volumes, customer behavior, and driver performance. It focuses on booking statuses, revenue breakdowns by payment method, and top customers. SQL queries are used to calculate ride statistics, and the final Power BI dashboard visualizes key data, including ride volumes, vehicle performance, and sales. The analysis helps optimize OLA's services by identifying trends and areas for improvement.
# Demo
<img width="1430" height="806" alt="Ola DA Project DEMO" src="https://github.com/user-attachments/assets/f78202c3-326f-468f-8abc-075495708d0d" />
SQL
# OLA Data Analyst Project SQL
# 📂 Introduction to the Database
This project involves analyzing ride bookings data for a ride-hailing service, "OLA." The database contains various tables (e.g., bookings, customers, and drivers) that store information about ride bookings, customer ratings, driver ratings, vehicle types, payment methods, and more.

The main objective of this project is to extract meaningful insights and statistics using SQL queries. This document showcases a set of queries to answer specific analytical questions about the business performance and customer behavior.

🛠️ How the Database Works
- Tables: The database is primarily focused on the bookings table, which contains the following key columns:

Booking_ID: Unique identifier for each ride.
Customer_ID: ID of the customer who booked the ride.
Vehicle_Type: Type of vehicle used (e.g., Prime Sedan, Auto, etc.).
Booking_Status: Status of the ride (e.g., Success, Cancelled by Customer, etc.).
Ride_Distance: Distance covered in the ride (in kilometers).
Payment_Method: Mode of payment used for the ride (e.g., UPI, Card, Cash).
Driver_Ratings: Ratings provided by customers to the drivers (out of 5).
Customer_Rating: Ratings provided by drivers to the customers (out of 5).
Booking_Value: Monetary value of the completed ride.
Incomplete_Rides: A flag to indicate whether the ride was completed or not.
Incomplete_Rides_Reason: If the ride was incomplete, this column stores the reason.
erstdgfhc
