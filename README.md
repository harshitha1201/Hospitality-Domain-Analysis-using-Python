# Data Analysis in Hospitality Domain: Atliq Grands Case Study
## Problem: 
Atliq Grands, a prominent Indian hotel chain, faced declining revenue and market share. This project leverages data analytics to improve their decision-making and regain a competitive edge.

## Solution:
### Data Source: 
Transactional booking data stored in a dedicated OLTP database, replicated into an OLAP data warehouse for analysis.
### Tools: 
Python, Jupyter Notebook, Pandas library.
## Steps:
- Data Understanding: Analyzing hotel, room, booking, date, and revenue data.
- Data Cleaning: Handling errors, outliers, and missing values.
- Exploration and Visualization: Gaining insights through descriptive statistics and visualizations.
- Insight Generation: Answering key questions for Atliq Grands managers:
+ Occupancy rate per room category and city.
+ Weekday vs. weekend occupancy comparison.
+ City-specific occupancy and revenue realized in June.
+ Revenue realized per hotel type and booking platform.
+ Average rating per city.

# 1. Business Problem Understanding : 
This is a hotel booking dataset of 4 cities in India. There are online portals to book rooms as per the standardization of the hotels class. The online portals are makeyourtrip, direct online, logtrip, tripster etc. The hotel owner wants the most revenue, profit as per hotel class and city and they want to expand their franchise in different cities based on the analysis. This hotel is facing challenges in market from their competitors and the owner wants to improve the revenue.

# 2. Data Collection and Data Understanding : 
Dataset 'dim_hotels' -> contains the data of hotel like hotel specifications, room quality, location of hotel
Dataset 'room' ->  data contains room dataset and class of the room which are Standard, Elite, Premium, and Presidential
Dataset 'dim_date'  -> contais the data of the date 
Dataset 'facts_data'  -> each entry of booking contains all data booking cancellation and no. of person in a room with there dates
Dataset 'facts_agrigatin' -> property id, booked and remaining rooms info
Denormalize database -> all data contains in one sheets
Normalize dataset-> records are seperated in tables based on properties and their application 

# 3. Data Cleaning and Exploration : 

Cleaned the data based on the mean, mode and median, also some of missing data rows are skipped for the analysis. Performed different joints on the dataset and explored to get some insights. 
Analysed each dataset and performed the analysis with different categories of application of hotel like city, hotelroom, etc

# 4. Data Transformation : 
Connected all datset and performed different analysis to get the all information based on categories. 
Added new columns for the analysis to calculate the percentage of the values and relationships with other datasets 

# 5. Data analysis and presentation : 
Finally analysed each category based on city, hotel type, occupancy, room quality, booking, plotted the gragh and analysed the report 

## Outcomes:
- Actionable insights to inform revenue-generating strategies.
- Improved understanding of booking patterns and guest preferences.
- Data-driven approach for future decision-making.
Additional Information:

This project highlights skills in data cleaning, exploration, analysis, and visualization.
The code and notebooks are available in this repository for further exploration.

Feel free to contact me for any questions or discussions!
