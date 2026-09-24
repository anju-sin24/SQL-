Airline DB & SQL Capstone Analysis
1. Project Overview -
This project analyzes AirlineDB, a comprehensive relational database covering flight bookings, ticketing, boarding passes, flight schedules, aircraft configurations, and airport data. Using advanced SQL queries, window functions, and complex joins, the project extracts key operational metrics, passenger trends, and flight performance insights.

2. Business Problem & Objectives -
Airlines manage vast amounts of transactional and operational data across bookings, flights, and airports, making it challenging to extract actionable insights from raw schemas alone. The objective of this project is to write optimized SQL queries to answer critical business questions, including:  
Booking & Ticketing Efficiency: Tracking ticket distribution and identifying missing check-ins or unutilized boarding passes.  
Flight & Airport Performance: Ranking airports by outbound flight volume and analyzing flight schedules.  
Data Transformation & Formatting: Standardizing date formats for accurate reporting and trend analysis.  
Sales & Product Performance: Utilizing CTEs and window functions (like ⁠RANK()⁠) to evaluate top-performing products, stores, or routes on a quarterly and cumulative basis.

3. Key Analytical Queries & Features -
The project solves multiple complex querying challenges, including:
Ticket vs. Boarding Pass Analysis: Identifying tickets issued without corresponding boarding passes using ⁠LEFT JOIN⁠ logic.  
Date Manipulation: Formatting timestamp and date fields into standard ⁠YYYY-MM-DD⁠ and ⁠YYYY-Q⁠ formats.  
Advanced Ranking & Window Functions: Implementing ⁠RANK() OVER (PARTITION BY ... ORDER BY ...)⁠ to determine top performers across categories and regions.

4. Tools & Technologies -
SQL: Advanced querying, Joins, Aggregations, Subqueries, CTEs (Common Table Expressions), and Window Functions.  
Relational Database Management System (RDBMS): Working with interconnected tables (⁠bookings⁠, ⁠tickets⁠, ⁠ticket_flights⁠, ⁠flights⁠, ⁠airports_data⁠, ⁠aircrafts_data⁠, ⁠seats⁠, ⁠boarding_passes⁠).
File Formats: ⁠.sql⁠ script files and documentation.

5. Data Source & Schema -
The relational database schema comprises multiple integrated tables:  
bookings⁠: Stores booking references, dates, and total amounts.  
⁠tickets⁠ & ⁠ticket_flights⁠: Contain passenger details, ticket numbers, flight segments, and fare conditions.  
flights⁠: Tracks flight schedules, departure/arrival airports, aircraft codes, and statuses.  
⁠airports_data⁠ & ⁠aircrafts_data⁠: Maintain airport metadata, coordinates, timezones, and aircraft model configurations.  
⁠boarding_passes⁠ & ⁠seats⁠: Manage seat assignments and check-in verifications.
