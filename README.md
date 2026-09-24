#AirlineDB-SQL-Analytics

#1. Project Overview - 
AirlineDB & Flight Operations Analytics is a comprehensive SQL-based project created to analyze airline bookings, flight schedules, ticketing data, passenger check-ins, aircraft configurations, and airport performance. The analysis provides a clear view of overall operational performance, route demand, booking trends, and passenger movement patterns.

#2. Business Problem -
Airlines generate large volumes of complex relational data across bookings, flights, and airports, making it difficult to extract performance metrics and operational bottlenecks through raw tables alone. The objective of this project is to write structured SQL queries to transform raw relational data into meaningful insights, helping management understand:  
* Booking patterns and total revenue generation.  
* Flight delay frequencies and schedule statuses.  
* Passenger check-in compliance and missing boarding passes.  
* Airport traffic volume and regional route distribution.  
* Quarterly sales performance and store/route rankings.

#3. Goal of the Analysis -
The main goal is to use advanced SQL query techniques—including Joins, Aggregations, Subqueries, Common Table Expressions (CTEs), and Window Functions—to evaluate operational and financial performance. The analysis allows stakeholders to filter and explore insights regarding:  
* Departure and Arrival Airports  
* Booking Dates and Quarters  
* Passenger and Ticket Categories  
* Flight Status and Check-in Analytics

#4. Tools & Technologies -
* SQL (PostgreSQL / MySQL): Advanced query writing, multi-table joins, and data extraction.  
* CTEs & Window Functions: Utilizing ⁠WITH⁠ clauses, ⁠RANK()⁠, and ⁠PARTITION BY⁠ for ranking and comparative metrics.  
* Date & String Formatting: Transforming timestamps using functions like ⁠TO_CHAR⁠ for standardized reporting.  
* Relational Data Modeling: Managing primary-foreign key relationships across tables (⁠bookings⁠, ⁠tickets⁠, ⁠ticket_flights⁠, ⁠flights⁠, ⁠airports_data⁠, ⁠aircrafts_data⁠, ⁠seats⁠, ⁠boarding_passes⁠).  
* File Formats: ⁠.sql⁠ script files containing optimized query solutions and documentation.
 
#5. Data Source -
* Source: Relational database (⁠AirlineDB⁠) containing structured tables covering passenger details, booking references (⁠book_ref⁠), ticket numbers (⁠ticket_no⁠), scheduled departures, actual arrivals, aircraft models, and seat layouts.
 
#6. Features / Highlights - Key Metrics & Analysis -
The SQL queries successfully extract the following key performance indicators and insights:
 Flight Operations Analysis -
 - Total flight volume and route distribution.  
 - Airport traffic ranking based on outbound flights.  
 - Identification of unutilized seats and missing passenger check-ins.  
 Booking & Revenue Trends -
 - Total booking amounts and ticket sales tracking.  
 - Quarterly sales comparison across operational hubs.  
 - Formatting booking dates into clean ⁠YYYY-MM-DD⁠ and ⁠YYYY-Q⁠ structures.  
 Advanced Analytical Insights -
 - Identifying top-performing routes using ⁠RANK()⁠ window functions.  
 - Finding discrepancies between issued tickets and generated boarding passes via ⁠LEFT JOIN⁠ operations.  
 - Analyzing aircraft model distributions and cabin class seat configurations.

#7. Key Insights -
The queries help uncover critical operational takeaways, including:
* High-traffic hub airports driving the majority of flight departures.  
* Seasonal trends and quarterly fluctuations in booking volumes.  
* Discrepancies in passenger check-ins where tickets were booked but boarding passes were unissued.  
* Effective revenue distribution across distinct fare conditions and aircraft classes.
