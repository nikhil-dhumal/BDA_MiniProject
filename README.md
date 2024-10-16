# **Flight Delay Analysis and Airline Performance Evaluation Using R**

## Project Overview
This project focuses on analyzing flight delays using a dataset of flight operations from various airlines. The analysis was performed using **R** to gain insights into flight performance, delays, and trends across different times of the day, airlines, and flight schedules.

## **Packages Used**
- **R**: Used for data manipulation, analysis, and visualization.
- **ggplot2**: For creating visualizations and plots.
- **dplyr**: For data wrangling and manipulation.
- **data.table**: For efficient data loading and handling large datasets.
- **lubridate**: For working with date and time formats.

## **Why This Dataset?**
This flight delay dataset offers significant insights into the performance and behavior of airlines. It allows us to:
- Analyze flight delays across different airlines, time periods, and days of the week.
- Investigate patterns of cancellations and diversions to identify performance issues.
- Evaluate how different factors, such as the airline and day of the week, affect delay times.
- Measure the impact of delays on airline schedules and how they vary by airline and flight path.

## **Methodology**
### **Data Preprocessing**
1. **Missing Values**: Handled by removing rows with missing values in key columns like `FlightDate`, `Airline`, and `DepTime`.
2. **Date and Time Conversion**: Columns like `FlightDate` and `DepTime` were converted to appropriate date and numeric formats for accurate analysis.
3. **Feature Engineering**: 
   - Created a `total_delay` feature to measure the combined departure and arrival delays.
   - Created a `day_of_week` feature from `FlightDate` to analyze delays by the day of the week.

## **Analysis and Visualizations**
1. **Line Plot: Flight Counts per Day of the Week**
   - **Purpose**: To understand flight traffic trends over the days of the week.
   - **Insight**: Flight counts vary by day, with specific days experiencing heavier traffic, which may help predict delays or congestion.

2. **Bar Plot: Average Departure Delay by Airline**
   - **Purpose**: To measure the average departure delay across different airlines.
   - **Insight**: Some airlines consistently have higher average delays than others, offering insights into performance variability.

3. **Bar Plot: Average Delay by Time of Day**
   - **Purpose**: To analyze how average flight delays vary across different times of the day.
   - **Insight**: Evening flights are most prone to delays, likely due to accumulated operational issues throughout the day.

4. **Line Plot: Average Delay per Day of the Week**
   - **Purpose**: To measure how delays change based on the day of the week.
   - **Insight**: Some days exhibit higher average delays, offering clues on which days travelers might face more issues.

5. **Bar Plot: Flight Volume by Time Block**
   - **Purpose**: To analyze the distribution of flight departures across different time blocks throughout the day.
   - **Insight**: The highest flight volume occurs in the morning (0600-1159), indicating peak operational hours and higher demand for morning flights.

## **Conclusion and Insights**
This project provides valuable insights into flight delays and airline performance:
- **Average Delays by Airline**: Some airlines show higher average delays, which could impact their reliability.
- **Day-of-Week Analysis**: Flight counts and delays vary across the week, with certain days exhibiting more flight activity and longer delays.
- **Delay Distribution**: Departure delays are concentrated around shorter durations, but significant outliers exist that cause operational issues.
- **Departure vs. Arrival Time**: There is a visible relationship between departure and arrival times across airlines, highlighting punctuality and recovery from delays.

## **Repository Contents**
- **R Scripts**: Contains all the scripts used for data manipulation, analysis, and visualizations.
- **Data Files**: Link to the dataset (if applicable).
- **Output Screenshots**: Visualizations generated from the analysis.

## **Data Source**
- The dataset used for this project is available on Kaggle: [Flight Delay Dataset](https://www.kaggle.com/datasets/robikscube/flight-delay-dataset-20182022?select=Combined_Flights_2022.csv).

## **Contributors**
- **Ayush Makade**
- **Nikhil Dhumal**
- **Swaraj Andhale**
- **Digvijay Mawale**

