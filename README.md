# SQL-capstone-Project
SQL project for data extraction, cleaning, and insight generation using real-world business data.

## Situation:
I worked with a complex airline reservation dataset simulating real-world scenarios involving bookings, tickets, flights, aircrafts, and boarding processes. The schema included interconnected entities like bookings, tickets, flights, airports, passengers, and boarding passes—providing a realistic platform for testing data modeling, querying, and relational understanding.

## Task:
- Design and execute SQL queries to:
- Extract key business metrics (e.g., flight frequency, booking trends, seat utilization)
- Validate booking and boarding logic (e.g., check-in restrictions, seat duplication)
- Analyze operational data for optimization opportunities
- Support real-world business rules using SQL logic

## Action:
- Explored and interpreted the schema to understand relationships among tables like tickets, ticket_flights, boarding_passes, aircrafts, and airports
- Designed advanced SQL queries using:
- JOINs and subqueries to connect bookings, passengers, and flights
- Window functions to rank flights, identify repeated routes, and calculate booking patterns
- Aggregate functions to summarize flight seat usage, boarding completion, and class distribution
- CASE logic to implement business rules like seat checks, class capacity checks, and round-trip identification
- Validated data integrity by ensuring:
- Each seat is uniquely assigned
- Passengers board only if their ticket includes the flight
- Optimized queries for performance by indexing key fields and minimizing nested logic

## Result:
- Delivered clean, accurate SQL outputs highlighting airline performance and booking behaviors
- Demonstrated real-world data modeling skills, handling normalization, relational joins, and airline-specific constraints
- Built foundational tools and queries that could be integrated into airline reporting dashboards or booking validation systems
- Strengthened SQL proficiency in areas of data cleaning, multi-table querying, and business logic implementation
