# data-analytics-capstone
A capstone project for the Google Data Analytics course that features a fictional bike-share company. 
## The six stages of analysis
### 1. Ask
The assignment was to find out how casual riders and members of Cyclastic, a fictinoal bike-share company, used its services differently, as well as what the two groups had in commmon.
### 2. Prepare
I downloaded the csv files for each of the previous 12 months (February 2021 - January 2022), then combined them into a single data table. I cleaned the data by removing rows where either the starting station ID or the ending station ID were NA. Privacy concerns didn't apply in this case, since the records contained no identifying information about customers: only data about the trips (date and time, starting point, ending point, bicycle type and rider type) but nothing else. 
### 3. Process
I wrote an R Markdown file to filter and process the data. I added calculated columns to show month, day of the week and ride duration. Rides with a length of 0 were filtered out. 
### 4. Analyze
I created three charts to show the differences between casual riders and members: Ride length by day of the week, rides by day of the week and rides by month. 
### 5. Share
I made csv files for each finding and uploaded them to Tableau to make charts. 
### 6. Act
A PowerPoint presentation puts the analysis in context and includes conclusions about the data and suggestions for next steps. 
