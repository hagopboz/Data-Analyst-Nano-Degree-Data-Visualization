# Ford Bike - Bay Area Data Analysis
## by Hagop Bozawglanian


## Dataset

I chose the data set for the Ford bike share service in the San Fransisco - Bay Area in the year 2017. 

The data covers 453,159 rows across 9 columns in 2017:

272 start stations 272 end stations 7 start month categories: Jun 2017 to Dec 2017 8 end month categories: Jun 2017 to Jan 2018 2 user types: Customer and Subscriber 7 age ranges: 18-24, 25-34, 35-44, 45-54, 55-64, 65-74, 75+ 3 gender types: Male, Female, and Other.

There was some data cleaning which included:

1. Drop unnecessary columns: 
   - start_station_name         
   - start_station_latitude     
   - start_station_longitude    
   - end_station_name           
   - end_station_latitude       
   - end_station_longitude      
   - bike_id      
2. remove 'nan' in member_gender
3. remove 'nan' in member_birth_year
4. convert start_time and end_time to date-time
5. convert member_birth_year to int
6. clean outliers in member_birth_year
7. member_birth_year column contain values as years, it should renamed to member_age and the values should be calculated


## Summary of Findings

After cleaning the data I was not able to find any more real outliers or any other data within the exploratory section to then include in the explanatory. I feel the data cleaning did an adequate job of normalizing the data to draw meaningful conclusions.


## Key Insights for Presentation

After looking at the data I think the interesting correleations I found were between the gender, age range, user status, and monthly information. I have included the valuable visualizations in the powerpoint as well as the notebook.

[Slideshow](https://hagopboz.github.io/Data-Analyst-Nano-Degree-Data-Visualization/explanatory_data_findings.slides.html#/)
