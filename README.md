# SQL-Database-Analysis
working on airline database using sql

SQL Database Analysis Project: Airline Database

**📝 Overview**

This repository contains a comprehensive set of 30 SQL queries designed to perform in-depth analysis on a relational database schema, typical of an airline or flight booking system. The project covers a wide range of analytical tasks, from basic data retrieval and formatting to complex subqueries, joins, and window functions for business intelligence insights.
The queries address real-world business questions related to passenger bookings, flight operations, aircraft details, and airport activity.

**✨ Key Features**

•The project demonstrates proficiency in SQL through the execution of the following key types of queries and analyses:

Data Formatting and Extraction: 

•Queries to format date/time columns (e.g., YYYY-Mon-DD format) and extract specific time components (e.g., EXTRACT(HOUR FROM...)) for filtering.

•Complex Joins and Data Aggregation:

•Extensive use of JOIN clauses (including INNER JOIN and NATURAL JOIN) across multiple tables (Bookings, Tickets, Flights, Boarding_passes, Aircrafts, Seats) to combine related information.

Business Logic Analysis:

•Identifying highest and least paying passengers on a monthly basis.
•Finding the longest flight duration and specific flight timings (morning flights).
•Determining the least allocated seat number.
•Identifying tickets without associated boarding passes.

Operational Insights:

•Counting flights between specific airports and from a list of airports.
•Analyzing flight status (Cancelled/Delayed) by aircraft model (Airbus, Boeing) and identifying refunds due to cancellations.
•Finding airports with the maximum and minimum number of scheduled departures.

Advanced SQL Techniques:

•Use of Window Functions (ROW_NUMBER() OVER (PARTITION BY ... ORDER BY ...)) to find the first/last flights of the day or first cancelled flights per airport.
•Applying HAVING clauses for filtering grouped data (e.g., flights with a return journey of more than one flight).
•Using LIMIT / FETCH NEXT 1 ROWS ONLY for top/bottom results.

**🛠️ Tools Used**

•SQL-The primary language used for querying, aggregating, and analyzing the database. The queries appear to be compatible with standard SQL
•Microsoft Word / Text Editor-Used to draft and document the SQL queries and expected outputs.

**✅ Conclusion**

This project serves as a robust portfolio piece, showcasing practical SQL skills essential for a Data Analyst or Database Developer role. The queries successfully transform raw operational data into actionable business intelligence, covering financial performance, operational efficiency, and customer-related metrics. The structured approach to problem-solving, utilizing both basic and advanced SQL features, ensures accurate and efficient data retrieval for complex analytical requirements.
