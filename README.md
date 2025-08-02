🚖 OLA Booking Analytics Dashboard – July 2024
📊 Project Overview
This project showcases a comprehensive analytics solution for OLA bookings during July 2024, combining:

📄 Excel – for raw data collection, formatting, and preprocessing

🧠 SQL – for advanced data cleaning, transformations, and aggregation

📊 Power BI – for interactive dashboard creation and visual storytelling

The dataset consists of 100,000+ rows, offering rich insights into booking patterns, vehicle usage, payment behavior, cancellations, and more.

🧾 Data Sources & Tools
Tool	Purpose
Excel	Initial data formatting, null checks, minor cleaning
SQL (SQLite/MySQL/PostgreSQL)	Data joins, filtering, KPIs, aggregations
Power BI	Data modeling, visual dashboards, user interface

📁 Dataset Highlights
📆 Period: July 1 – July 31, 2024

📌 Records: 103,024 bookings

💰 Booking Value: ₹35 Million

🛣️ Distance Tracked, Status, Vehicle Type, Payment Mode, and more

📊 Dashboard Sections
1. 🟢 Overall Summary
Total Bookings: 103,024

Successful Rides: 63,967 (62.09%)

Cancelled Rides: 28,933 (28.08%)

Total Revenue: ₹35M

Booking Status: Pie chart breakdown

Trendline: Daily ride volume

2. 🚗 Vehicle Type Analysis
Metric	Observation
Top Earner	Prime Sedan – ₹8.30M
Most Efficient	E-Bike – Highest success & distance (25.15 km avg)
Least Travelled	Auto – Avg distance: 10.04 km

Columns Analyzed:

Vehicle Type

Total/Success Booking Value

Avg & Total Distance Travelled

3. 💸 Revenue Insights
Top Payment Mode: Cash (~₹19M)

UPI Usage: ~₹14M

Card Usage: Minimal (Credit & Debit combined <2M)

Top 5 Customers: Tracked by booking value

Visuals: Bar chart by payment method + daily revenue trend

4. ❌ Cancellations Deep Dive
Overall Cancellation Rate: 28.08%

Customer Cancellations:

Main reason: "Driver not moving toward location" (30.42%)

Driver Cancellations:

Main reason: "Personal & Car related issues" (35.49%)

Includes dual pie charts with segmented reasons

🌟 Ratings Overview
The Ratings section presents customer and driver satisfaction scores across all vehicle types for July 2024.

🧑‍✈️ Driver Ratings (Out of 5)
Vehicle Type	Rating
Prime Sedan	3.99
Prime SUV	4.01
Prime Plus	4.00
Mini	3.99
Auto	4.00
Bike	3.98
E-Bike	4.01

👥 Customer Ratings (Out of 5)
Vehicle Type	Rating
Prime Sedan	4.00
Prime SUV	4.00
Prime Plus	4.01
Mini	4.00
Auto	4.00
Bike	3.99
E-Bike	3.99

Key Takeaways:

Ratings are generally high, indicating a strong level of service.

Prime SUV and E-Bike received the highest driver satisfaction (4.01).

Prime Plus leads in customer satisfaction (4.01).

Ratings for Auto services remained consistently positive (4.00 for both drivers and customers).

💡 Key Insights
Over 60% rides are successful – OLA has good operational efficiency.

28% cancellation rate – mostly driven by location and vehicle availability issues.

Cash still dominates over digital payment methods.

E-Bikes are rising in success rate and average distance — good green initiative.

📌 Challenges Faced
🗃️ Handling large datasets (>100k rows) in Excel and SQL

🧮 Complex DAX and calculated columns for performance metrics

🧹 Manual data cleaning before ingestion into Power BI

✅ Final Dashboard Capabilities Summary
The Power BI dashboard offers:

A full view of operational health for OLA in July 2024.

Analysis across 100k+ rows of data using SQL + Excel.

Insights into bookings, payments, vehicle performance, ride trends, cancellations, and satisfaction ratings.

