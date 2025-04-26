# Ford GoBike Sharing Analysis

## Project Description
This project focuses on exploring, analyzing, and deriving business strategies for the Ford GoBike Sharing Service using trip-level data collected over a period of time.  
The study covers user behavior patterns based on demographics, trip durations, usage timings, and station popularity to help suggest actionable strategies for business growth.

## Objective
The main objectives of this project are:
- To understand bike-sharing user behavior across different demographics.
- To analyze trip patterns based on time, gender, and age groups.
- To identify opportunities for operational improvements.
- To suggest strategic marketing and service enhancements to improve profitability and customer satisfaction.

## Data Description
- **Source**: Ford GoBike System Data
- **Format**: CSV file
- **Size**: Approximately several thousand trip records
- **Fields Included**:
  - Trip Duration (seconds and minutes)
  - Start and End Time
  - Start and End Station Names and IDs
  - Bike ID
  - User Type (Subscriber or Customer)
  - Member Birth Year
  - Member Gender
  - Bike Share for All Trip (Yes/No)

## Exploratory Data Analysis (EDA)
The following analyses were conducted:
- Scatter Plot of Trip Duration vs Age
- Hourly Trip Start Analysis by User Type
- Gender Distribution Analysis
- Age Distribution and Age Group Analysis
- Most Popular Start and End Stations
- Trip Duration Comparison by Gender
- Correlation Heatmap between Numerical Features
- Pair Plot Analysis of Key Variables
- Participation in Bike Share for All Program
- Weekly Usage Trends

## Insights
- Majority of the riders are aged between 20 to 40 years.
- Male users are significantly higher compared to female users.
- Subscribers mainly use bikes during commuting hours (morning and evening).
- Customers take longer rides and are more active during weekends.
- Certain stations have extremely high traffic, indicating the need for strategic station management.
- Participation in the Bike Share for All Program is more common among casual riders.

## Conclusion
The Ford GoBike system shows strong traction among young commuters, but there is untapped potential among older demographics and casual riders.  
Operational adjustments, targeted marketing strategies, expansion of community programs, and dynamic pricing models can help the business achieve sustainable growth, higher profitability, and a more diverse customer base.

## Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook
