Project Title: Riders and Transportation Sites Analysis ( NYC Data Analysis)

Project Description
This project analyzes pre-kindergarten (PreK) transportation data across various sites in New York City, utilizing three datasets: "Riders by Transportation Site," "Routes by Transportation Sites," and "Transportation Sites." The objective is to explore transportation patterns, site characteristics, and routing data, and to present findings in a meaningful, data-driven format. This analysis will provide insights into rider distribution, route allocation, and site-related services across multiple school years.

Datasets

Riders by Transportation Site

Description: Contains data on PreK riders, showing the number of students transported to different sites each school year.
Columns:
School Year: Academic year of the data.
Site Name: The destination site of the riders.
School Name: Name of the school associated with the site.
Number of Riders: Total number of students transported to the site.
Routes by Transportation Sites

Description: Details transportation routes across different sites and school years, allowing for route analysis across locations.
Columns:
School Year: Academic year of the data.
Route Number: Identifier for each transportation route.
OPT Code: Unique identifier for each site.
Transportation Sites

Description: Provides detailed information about each transportation site, including site location, service offerings, and type.
Columns:
Site Name: Name of the transportation site.
Type: Type of site (e.g., school).
Address, City, Zip Code: Location details for mapping and geographic analysis.
Service Attributes: Information on services provided at the site (e.g., door-to-door service, mid-day service).
Coordinates: Latitude and longitude values for mapping locations across NYC.
Project Objectives

Analyze transportation patterns, such as the number of riders per site, route allocations, and site services.
Visualize trends over different school years, focusing on the distribution of PreK riders, route associations, and site service coverage.
Create a user-friendly presentation of the data on an interactive map to help visualize transportation coverage across NYC.
Features

Data Cleaning and Preprocessing: Address missing values, standardize site and school names, and ensure accurate geolocation for mapping.
Yearly and Site-Based Comparative Analysis: Analyze changes in ridership across years, identify site-specific trends, and compare routes by site.
SQL Queries: Use SQL to query, aggregate, and manipulate data for efficient analysis and reporting.
Programming Language: Python

Libraries

Pandas: For data manipulation and analysis
Matplotlib/Seaborn: For data visualization
Folium/Plotly: For creating interactive maps
