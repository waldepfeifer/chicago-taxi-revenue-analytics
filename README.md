<img width="1295" alt="image" src="https://github.com/user-attachments/assets/eb849a83-a69b-4316-b22b-1bb2541ca75f" />

## Project Overview

This project analyzes public taxi trip data from the City of Chicago to identify cost-saving strategies and new revenue opportunities for a local taxi company.  
The analysis uses detailed ride-level information such as trip duration, distance, fares, tips, and geographic zones to extract actionable business insights.

## Objectives

- Understand trip-level patterns including mileage, duration, and fare amounts  
- Identify high-demand zones and timeframes based on pickup and dropoff data  
- Analyze customer tipping behavior  
- Explore operational inefficiencies in route and pricing structures  
- Provide recommendations to increase revenue and reduce costs for taxi operations

## Tools and Libraries

- Python 3.x  
- pandas  
- NumPy  
- matplotlib  
- datetime parsing and timestamp conversion

## Project Structure

chicago-taxi-data-analytics/  
├── chicago_taxi_trip_insights_and_revenue_opportunities.ipynb   – Main analysis notebook  
├── Taxi_Trips_october.csv                                       – Dataset used in the project  
├── README.md                                                    – Project documentation  

## Dataset Description

- Source: [City of Chicago Taxi Trips Open Dataset](https://data.cityofchicago.org/Transportation/Taxi-Trips/wrvz-psew)  
- File: Taxi_Trips_october.csv  
- Data fields include:
  - unique_key: Unique trip ID  
  - taxi_id: Anonymized vehicle ID  
  - trip_start_timestamp, trip_end_timestamp  
  - trip_seconds, trip_miles  
  - pickup and dropoff community areas  
  - fare, tips, tolls, extras  

- Timestamps are rounded to 15-minute intervals  
- Census tract and some sensitive fields may be omitted to protect privacy  

## Analysis Highlights

- Date range coverage: derived from timestamp parsing  
- Tip distribution and average fare values  
- Time-of-day trip analysis  
- Most frequent pickup/dropoff areas  
- Ride length vs. profitability correlation  
- Suggestions for optimized operations based on trip patterns

## How to Run

1. Clone the repository  
2. Ensure Python 3.x is installed  
3. Install necessary packages:  
   pip install pandas numpy matplotlib  

4. Place `Taxi_Trips_october.csv` in the project root  
5. Open and run the notebook:  
   `chicago_taxi_trip_insights_and_revenue_opportunities.ipynb`

## Requirements

- pandas  
- numpy  
- matplotlib  

Install using:  
pip install pandas numpy matplotlib

## License

This project is licensed under the MIT License. See the LICENSE file for details.
