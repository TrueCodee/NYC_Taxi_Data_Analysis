# NYC Taxi Data Analysis

## Overview
This project performs an in-depth analysis of NYC yellow taxi trip data to uncover patterns and insights related to trip durations, fare amounts, peak hours, and popular pickup and drop-off locations. The analysis was conducted using PySpark on Databricks to efficiently process and analyze large datasets.

## Dataset
- **Source**: NYC Yellow Taxi Trip Data (January 2015)
- **Description**: This dataset includes various details about yellow taxi trips, such as pickup and drop-off times, trip distances, fare amounts, passenger counts, and pickup and drop-off locations.
- **Key Columns**:
  - `tpep_pickup_datetime` & `tpep_dropoff_datetime`: Timestamps of when the trip started and ended
  - `trip_distance`: Distance of the trip in miles
  - `fare_amount`: Fare charged for the trip
  - `passenger_count`: Number of passengers on the trip
  - `pickup_longitude` & `pickup_latitude`: GPS coordinates of pickup location
  - `dropoff_longitude` & `dropoff_latitude`: GPS coordinates of drop-off location

## Key Analyses and Insights
1. **Trip Duration Analysis**: Examined trip duration trends by hour and day to identify peak times.
2. **Fare Amount Analysis**: Analyzed how fare amounts vary based on pickup locations and passenger count.
3. **Hotspot Identification**: Mapped the most frequent pickup and drop-off locations, revealing high-demand areas.
4. **Hourly Demand Analysis**: Investigated demand patterns throughout the day to understand peak taxi usage hours.
5. **Correlation Analysis**: Explored relationships between trip duration, trip distance, and fare amount.

## How to Run
### Prerequisites
1. **Databricks**: Set up a Databricks environment to run PySpark code. Alternatively, use a local PySpark setup.
2. **Required Libraries**:
   - `PySpark`
   - `Pandas`
   - `Matplotlib`
   - `Seaborn` (for visualizations)
   
### Steps
1. Clone this repository:
   ```bash
   git clone https://github.com/TrueCodee/NYC-Taxi-Data-Analysis.git
2. Upload CP422 - A1 - G17.ipynb to Databricks or open it in your local Jupyter environment.
3. Run each code cell in sequence to perform the analysis.

## Project Structure
- CP422 - A1 - G17.ipynb: Jupyter Notebook with the complete analysis and visualizations.
- CP422 - A1 - G17 - Databricks.pdf: PDF version of the notebook for quick reference.
- README.md: Project overview and instructions.

## Summary of Findings
- **Average Fare by Hour:** Fares tend to be higher in the early morning hours (4-6 AM), with the lowest fares around 7 PM, likely due to competition during peak demand times.
- **Trip Duration Patterns:** Peak demand occurs between 6 PM and 10 PM, aligning with the most frequent pickup hours.
- **Popular Locations:** Certain GPS coordinates show high pickup and drop-off frequencies, identifying hotspots that could inform targeted marketing or service allocation.
- **Fare and Distance Relationship:** A moderate correlation exists between trip fare and distance, as expected, while trip duration and fare show a weaker correlation due to variability in traffic and route efficiency.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
