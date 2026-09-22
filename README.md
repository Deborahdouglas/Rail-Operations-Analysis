# Rail-Operations-Analysis
An analysis of rail operations to understand passenger traffic, revenue performance, peak travel periods, and key operational trends using Power BI.
# Project overview
This project analyzes rail operations to better understand how passengers use the rail service and how different operational factors affect revenue and passenger movement. Using the available rail data, I explored passenger traffic patterns across different days and times of the day to identify when demand is highest. I also analyzed revenue across different routes, identified stations with the highest number of passengers, and examined the payment methods passengers use most often. The insights from this analysis can help rail operators better understand passenger behaviour, identify busy periods, monitor route performance, and support decisions that can improve planning and overall rail operations.
# Business Questions
This project was carried out to answer the following business questions:
- What day has the highest passenger traffic?
- What time of day experiences peak demand?
- Which routes generate the highest revenue?
- Which stations handle the most passengers?
- What payment methods are most commonly used?
# Datasets
This project used six related datasets covering different aspects of rail operations. The datasets include information on fare pricing, payment methods, rail routes, passenger traffic, trains, and ticket sales.

The datasets used were:
fare_pricing_dim
payment_methods_dim
rail_routes_dim
rail_traffic_fact
rail_trains_dim
ticket_sales_fact

The datasets were used together to analyze passenger traffic, travel patterns, route revenue, station activity, and payment methods.

# Data Preparation
The datasets were prepared in Microsoft Excel before being imported into Power BI. The original data did not require major cleaning.

A new column was added to categorize travel times into Morning, Afternoon, and Night. This made it easier to analyze passenger traffic by time of day and answer the question of when peak demand occurs.

A Date Table was also created in Power BI to support date-based analysis and help organize the data for the dashboard.

# Tools Used
- Microsoft Excel – Used to prepare the datasets and create the time-of-day category.
- Power BI – Used to create the data model, analyze the data, create measures, and build the interactive dashboard.
- DAX – Used to create calculated measures and support the analysis in Power BI.

# Key Findings
- The analysis covers a railway network of 10 routes and 25 stations, generating a total revenue of 2.29M from 641K passengers from 2024-2025
- Passenger traffic is fairly consistent across the week, with Tuesday recording the highest volume. Night hours drive the most travel demand, accounting for 213K passengers. University Station tops passenger count among all 25 stations at 25.98K.
- The Metro Rapid line leads in revenue at 360.92K, followed by Green Valley and Airport Line. When filtered by train type, Express trains generate the highest revenue and carry the most passengers compared to Intercity and Metro services.
- Payment methods are evenly distributed across Card, Cash, Contactless, and Mobile App each at approximately 25% - reflecting broad accessibility across passenger segments.
