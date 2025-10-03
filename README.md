# Phase_1_project


OVERVIEW
The primary objective of this project is to determine which aircrafts are the lowest risk for the company to start its venture into purchasing and operating airplanes for commercial and private enterprises by analyzing potential risk of aircrafts.

The project will leverage data from "AviationData.csv" which contains historical aircraft data to identify lowest risk aircraft models using statistical analysis and data visualization The data contains Injury Severity, Aircraft Damage and Accident frequency .


BUSINESS UNDERSTANDING
The company is looking to expand it into purchasing and operating aircrafts for commercial and private enterprises but its facing uncertainty in selecting the safest and reliable aircraft without understanding the potential risk associated with different aircraft models including accidents rate, injury severity and Aircraft damage.

Without perfect understanding the company risks investing in high-risk aircraft that could lead safety concerns and financial loss. This project aims to leverage aviation data to obtain meaningful insight to identify the lowest risk aircraft models providing the company with actionable insight to make informed decisions about aircraft. 


DATA UNDERSTANDING
- Focused on key variables: Injury.Severity, Aircraft.Damage, and    injury counts (Fatal, Serious, Minor, Uninjured)
 - Removed missing values from key variables
 - Converted injury columns from object to integer for analysis
 - Grouped data by Make_Model for aggregated risk insights


DATA ANALYSIS
For the data analysis my analysis was based on aircraft model, engine type, purpose of the flight , Fatalities(Fatal injury) and and also created the Fatality rate to help with my analysis which focused on:
         ● Top 10 most dangerous aircraft based average fatalities
          - This      generated the top ten dangerous aircraft based on make and model
          ● Total Fatalities based on the Purpose of the purpose of the flight
          - this generated dangerous aircraft based on the purpose of the aircraft flight
         ● Average Fatality rate based on engine type 
          - This generated top ten dangerous Engine type of the aircrafts based on the fatality rate


RECOMMENDATION
1. Aircraft Model Risk – Avoid High-Fatality Aircraft
     ● The company should avoid aircraft models listed among the Top 10 most dangerous (based on average fatalities).
     ● They should focus on aircraft models with lower accident fatality averages, indicating better crash survivability.
 2. Flight Purpose Risk
     ● Limit operations in flight purposes with high total fatalities
     ● Focus on business, instructional, or commercial flight categories that demonstrated lower fatality counts.
 3. Engine Type Risk
     ● The company should also focus aircraft with engine types in the Top 10 highest average fatality rates.
     ● The company should Prefer aircraft with proven, lower-risk engine types based on historical fatality data
