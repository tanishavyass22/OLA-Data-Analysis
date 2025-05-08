# 🚖 Ola Ride Booking Analysis — July 2024
### This repository features a detailed dashboard and in-depth analysis of over 1 lakh Ola ride booking records for July 2024. The dataset, generated using ChatGPT, has been explored and visualized using Excel, Power BI, SQL, and statistical techniques. This project aims to uncover meaningful insights into ride patterns and customer behavior, supporting data-driven decision-making.
Prompt for generating the data:
 Please create a spreadsheet with 1 lac rows, for Bengaluru city. Give the following columns.
 The data will be for 1 month. use the following column
1. Date
 2. Time
 3. Booking ID
 4. Booking Status
 5. Customer ID
 6. Vehicle Type- Auto- Prime Plus- Prime Sedan- Mini- Bike- eBike- Prime SUV
 7. Pickup Location (Create dummy location points Take any 50 areas from Bangalore)
 8. Drop Location (Take from dummy pickup locations)
 9. AvgVTAT (Time taken to arrive at the vehicle)
 10. Avg CTAT (Time taken to arrive the Customer)
 11. Cancelled Rides by Customer
 12. Reason for cancelling by Customer
Driver is not moving towards pickup location----
 Driver asked to cancel
 ACis not working (Only for 4-wheelers)
 Change of plans
 Wrong Address
 13. Cancelled Rides by Driver
Personal & Car related issues--
Customer related issue
 The customer was coughing/sick
 More than permitted people in there
 14. Incomplete Rides
 15. Incomplete Rides Reason
Customer Demand--
 Vehicle Breakdown
 Other Issue
 16. Booking Value
 17. Ride Distance
 18. Driver Ratings
 19. Customer Rating
 Keep the overall booking status success for this data at 62%. If the booking status is successful, then only
 fare charge ratings, average VTAT, average CTAT, and other data will be there.
 Make sure orders cancelled by customers should not be more than 7%
 Make sure orders cancelled drivers should not be more than 18%
 keep incomplete rides less than 6%
 Keep order value high on weekends
