# OLA-Performance-Analytics
Analysis of trends in Bookings,Cancellations,Revenue,Ratings.. using Sql and Power BI

Dataset:
Generated sample dataset of 1,00,000 rows for Bengaluru city using ChatGpt prompts and organized into a structured spreadsheet with the following Data columns:
1. Date
2. Time
3. Booking_ID
4. Booking_Status
5. Customer_ID
6. Vehicle_Type
7. Pickup_Location
8. Drop_Loaction
9. V_TAT
10. C_TAT
11. Cancelled_Rides_by_Customer
12. Cancelled_Rides_by_Driver
13. Incomplete_Rides
14. Incomplete_Rides_Reason
15. Booking_Value
16. Payment_Method
17. Ride_Distance
18. Driver_Ratings
19. Customer_Rating
20. Added an adiitional column of "Payment_Mode" using if Condition in excel Sheet

Views of multiple sheets in the PowerBI:

Overall
* Total Bookings
* Total Booking Value
* Booking Status Breakdown
* Ride Volume Over Time

Vehicle Type:
* Toatl Bookings of each type of Vehicle
* Success Booking Value of each type of Vehicle
* Average Distance Travelled by each type of Vehicle
* Total Distance Travelled by each type of Vehicle

Revenue:
* Revenue by Payment Mode
* Revenue BY Top 5 Customers
* Ride Distance Distribution per day

Cancellation:
* Cancelled Rides by Customer
* Cancelled Rides by Driver
* Suceeded Bookings
* Cancelled Bookings
* % of Cancellation rate

Ratings:
* Driver Rating for each Vehicle Type
* Customer Ratings for each Vehicle Type

Conclusion

Based on the July ride data, Ola achieved 1,00,000 bookings worth ₹31M, but nearly 31% of rides were lost due to cancellations or incompletions. Driver cancellations (24.7%) and customer cancellations (20%) are the biggest revenue leakages, costing around ₹7.7M. SUVs and Bikes are the top revenue drivers, while E-Bikes show very high utilization, making them a strong growth area. However, customer ratings are only around 4.0, with lower satisfaction in Mini, Auto, and E-Bike rides. To boost revenue, Ola should reduce cancellations with better driver incentives, improved app accuracy, and service quality checks. Expanding high-performing categories (SUV, Bike, E-Bike), launching loyalty programs like one free ride after 10 rides,discounts on special days can also drive growth. With these changes, Ola could increase revenue by 15–20% and improve customer retention significantly.
