# Geospatial Rides Analysis

This repository contains a take-home exercise focused on analyzing ride data using SQL, Pandas, and geospatial queries in Databricks. The task involves data cleaning, exploration, and deriving insights from a dataset of 1000 rides.

## Task Overview

You are given a dataset of rides with pickup and drop-off locations, timestamps, and fare amounts. Your objective is to perform data cleaning, run geospatial queries, and derive meaningful insights.

## Dataset
- **File**: `data/rides.csv`
- **Columns**:
  - `ride_id`: Unique identifier for each ride
  - `pickup_lat`, `pickup_lon`: Pickup latitude and longitude
  - `dropoff_lat`, `dropoff_lon`: Drop-off latitude and longitude
  - `ride_timestamp`: Date and time of the ride
  - `fare_amount`: Fare charged for the ride (can contain negative, zero, or null values)

## Tasks

Each task should be performed in a separate cell.

1. **Data Ingestion:**
   - Load the CSV file into a DataFrame using Pandas.
   - Inspect the first few rows and check for null values.

2. **Data Cleaning:**
   - Handle missing values in pickup and drop-off coordinates.
   - Remove or flag rides with negative and zero fares.
   - Example:
     - Example Row: `ride_id: 2, pickup_lat: None, pickup_lon: None, dropoff_lat: 12.9352, dropoff_lon: 77.6245, ride_timestamp: '2025-03-24 09:00:00', fare_amount: -50.0`

3. **Analysis and Insights:**
   - Calculate the average fare per kilometer.
   - Identify the top 5 busiest pickup locations.
   - Find rides with unusually high or low fares based on distance.
   - Example:
     - Example Row: `ride_id: 3, pickup_lat: 12.9716, pickup_lon: 77.5946, dropoff_lat: 12.9716, dropoff_lon: 77.5946, ride_timestamp: '2025-03-24 10:00:00', fare_amount: 1000.0`

4. **Visualization:**
   - Group rides by hour to determine peak ride times.
   - Visualize pickup and drop-off points on a scatter plot.
   - Example:
     - Example Row: `ride_id: 4, pickup_lat: 12.9352, pickup_lon: 77.6245, dropoff_lat: 12.9352, dropoff_lon: 77.6245, ride_timestamp: '2025-03-24 17:00:00', fare_amount: 300.0`

## Submission Guidelines
- Provide a Jupyter Notebook or Databricks notebook with your code and explanations.
- Include visualizations if possible.
- Share key insights and observations at the end.

## Evaluation Criteria
- Data cleaning and handling of edge cases.
- Correctness of geospatial queries.
- Quality of analysis and insights.
- Code readability and documentation.

Happy coding! 🚀

