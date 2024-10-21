# Airport Geospatial Analysis using PostgreSQL

# Project Overview:

This project demonstrates the use of PostgreSQL with PostGIS extension for geospatial data analysis using a dataset from OurAirports. The goal is to manage and query airport data efficiently by leveraging spatial data types and functions such as the locations of specific features, distances between points, and areas of interest, using indexing, aggregate and join executors, sort+ limit executors, sorting, and top-N optimization.

# Dataset Source:

The dataset is sourced from OurAirports, a platform that provides comprehensive geospatial data related to airports worldwide. The dataset (airports.csv) contains up-to-date geospatial information on global airports.

# Features

**Database Setup**

PostGIS Installation: To enable geospatial queries, the PostGIS extension is installed in PostgreSQL

Table Creation: The airport's table is created to store attributes like airport name, type, location (latitude and longitude), and codes (IATA, ICAO).

**Data Imports**

The COPY command is used to load the airport data into the database from a CSV file.

**Geospatial Data Handling**

Adding a geometry column to store geographic data (latitude and longitude) as spatial points.

# Key Learnings

PostGIS Functionality: This project demonstrates how to use PostGIS functions like ST_SetSRID, ST_MakePoint, and ST_Distance for geospatial data manipulation.

Query Optimization: By using indexes and query optimization techniques, we were able to significantly improve the performance of queries involving large datasets.

# Project Summary:

This project has been a significant exploration into the world of geospatial databases using PostgreSQL and its PostGIS extension. We sourced comprehensive airport data from OurAirports and successfully integrated this extensive dataset into our database. This allowed us to perform various queries, calculations, and analyses on the data, exploring the capabilities of PostGIS extension and learning how to use SQL for geospatial analysis.

By creating indexes and implementing N-Optimization techniques, we were able to optimize our queries, leading to faster and more efficient data retrieval. We gained practical insights into handling and optimizing large datasets, and understanding the balance between query performance and the computational cost of maintaining indexes.

# Future Studies/Improvements

Explore additional PostGIS functions for more complex spatial analysis, such as spatial joins and clustering.

Implement visualizations of geospatial data using tools like QGIS or integrating with web mapping libraries.
