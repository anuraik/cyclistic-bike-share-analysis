# 🚲 Cyclistic Bike-Share Analysis

## 📌 Project Overview

This project analyses bike-share usage patterns to understand how different types of riders use the service.

The analysis covers ride frequency, ride duration, weekly patterns, and the most popular start and end stations.

## 🎯 Business Question

How do casual riders and annual members use bike-share services differently and what insights can help convert casual riders into annual members?

## 🛠️ Tools

- Excel
- SQL
- Data visualization

The analysis covers:

- Number of rides
- Ride duration
- Weekly patterns
- Differences between casual riders and annual members
- Popular start and end stations

## 🧹 Data Cleaning

The dataset was cheked and prepared before analysis. 

The following steps were performed:

- Checked for missing values
- Checked the data types
- Calculated ride duration
- Created day-of-week variables
- Checked the distribution of rider types
- Reviewed station data for missing values

## 📊 Analysis

The analysis examined:

### Rider Type

The analysis compared the number of rides made by casual riders and member riders. Casual riders made up 28% and member riders made up to 72% of total riders. Although there were significally less casual riders, in terms of duration, they rode bicycles more. 

### Ride Duration

Compared the average ride duration between casual riders and annual members. Average ride lenght was 3,5x times longer for casual riders then member riders. 

### Weekly Patterns

Analysed average ride duration by day of the week. For casual riders, the most popular day was Friday. Member riders used this service most on Saturday and Sunday. For casual riders, the lowest day was Sunday and for member riders it was Wednesday. 

Possible explanation for these results is that casual riders use bikes more for leisure activities or longer rides, as member riders use bikes more for regular and practical movements. 

### Popular Stations

The analysis identified top 5 start stations and top 5 end stations. 
Top 5 start stations were: 
- Clark St & Elm St
- Dearborn St & Erie St
- Desplaines St & Kinzie St
- St. Clair St & Erie St
- Clark St & Armitage Ave

Top 5 end stations were: 
- Dearborn St & Erie St
- St. Clair St & Erie St
- Desplaines St & Kinzie St
- Broadway & Barry Ave
- Wabash Ave & Roosevelt Rd

From those list, there are 3 stations that are overlaping. Dearborn St & Erie St, Desplaines St & Kinzie St and St. Clair St & Erie St are on top 5 on both list. Those station maybe the most important locations and there can be a large demand around those areas. From logistical planning (e.g. redistributing bikes), those stations are most impostant. 
Bike share company can focus in those areas more on: 
  - advertising membership
  - QR-code campains
  - introtucing the benefits of memebership


## 🔍 Key Findings

- The dataset contains 84,756 rides, with casual riders accounting for 72% of all rides and members for 28%. 
- Casual riders have a significally higher average ride duration than members (1:12h vs. 0:21h).
- Casual riders use ride share aproximately 3,5 times longer than member riders. 
- Casual riders have longer average ride durations across all week, with Friday being the longest. 
- 3 stations out of top 5 start and end stations overlaped.
- A relatively small number of stations account for a large share of rides, with several popular stations appearing among both the top start and end stations.
- The usage patterns suggest that casual riders and members use the bike-sharing service differently.

## 💡 Recommendations

Based on the analysis, the following recommendations could help increase annual memberships:

- Target casual riders with membership offers focused on the benefits of frequent and longer-term bike usage.
- Promote membership benefits during periods with high casual rider activity.
- Use popular stations as locations for targeted membership campaigns.
- Highlight the potential value of membership for frequent casual riders.

## 📈 Visualizations

- Average ride lenght by day
- Average ride lenght casual vs member
- Member vs casual by numbers
- Top 5 start stations
- Top 5 end sattions


## 📁 Data Source

Data source: https://divvy-tripdata.s3.amazonaws.com/index.html

The raw dataset is not included in this repository because of its large file size.

## 👩‍💻 Author

Anu Raik


README.md
