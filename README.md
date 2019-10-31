# 2019-NYC-Airbnb-Property-Data-Analysis

Group Project 1 involved choosing a dataset from an external source, using Python to process the data, and performing analysis based on generated visualizations. The members of the group are Sedra Kurdi, Myles Bridges, Natalie Myers, and Matthew Kennedy. The approach was to clean the data, and then process and analyze it at the city, borough, and neighborhood levels. Parameters identified for consideration included property type, price, availability for booking, minimum night requirement, and number of reviews.





## Questions



### New York City Level



1. What is the number and percentage of property types (entire home/apartment, private room, shared room) available?

2. How many unique hosts are there for each type of property?



### New York City Borough Level



1. What is the number and percentage of property types available in each borough?

2. What is the average number of days available for booking for each type of property in each borough?

3. What is the average price for each type of property in each borough?

4. What is the average number of minimum nights for each type of property in each borough?



### New York City Borough's Neigborhoods



1. In each borough, what are the five neighborhoods with the most reviews?

2. In each borough, what are the five neighborhoods with the highest property type counts?

3. In each borough, what are the five neighborhoods with the highest and lowest average prices for each property type?

4. In each borough, what are the five neighborhoods with the lowest average minimum night requirement?



## Datasets



1. https://github.com/mjknj18/2019-NYC-Airbnb-Property-Data-Analysis/blob/master/Airbnb%20Data/AB_NYC_2019.csv



## Tasks



### Data Import & Cleaning

1. Import the 2019 NYC Airbnb Property dataset as a Pandas dataframe.
2. Remove rows containing "N/A" values in any column.
3. Remove rows containing inaccurate values in any column. 





### New York City Level

#### Property Type Counts

1. Group cleaned data by property type.
2. Count total occurances of each property type.
3. Plot bar graph of total property counts.

#### Unique Host Counts
1. Group cleaned data by property type and filter by host identification number.
2. Count total nummber of unique host identification numbers per property type.
3. Plot bar graph of unique hosts per property type.





### New York City Borough Level

#### Property Type Counts & Percentage

1. Group cleaned data by borough and property type.
2. Count total occurances of each property type in each borough.
3. Calculate percentage of each property type in each borough.
4. Create pie charts of property type distribution in each borough.

#### Property Type Average Availability

1. Group cleaned data by borough and property type, and filter by availability.
2. Calculate average availability of each property type in each borough.
3. Plot bar graph of average property type availability per borough.

#### Property Type Average Price

1. Group cleaned data by borough and property type, and filter by price.
2. Calculate average price per property type in each borough.
3. Plot bar graph of average property type price per borough.

#### Property Type Average Minimum Night Requirement

1. Group cleaned data by borough and property type, and filter by minimum night requirement.
2. Calculate average minimum night requirement per property type in each borough.
3. Plot bar graph of average property type minimum night requirement per borough.





### New York City Borough's Neigborhoods

#### Most Reviews

1. Group cleaned data by borough and neighborhood, and filter by number of reviews.
2. Calculate average number of reviews for each neighborhood in each borough, and sort results from highest to lowest.
3. Plot line graph of top five neighborhoods in each borough with the most reviews.

#### Highest Property Type Counts

1. Group cleaned data by borough and neighborhood, and filter by property type.
2. Calculate total occurances of each property type in each neighborhood of each borough, and sort results from highest to lowest.
3. Plot line graphs for each property type of the top five neighborhoods in each borough with the highest counts of that property type.

#### Highest Average Price

1. Create dataframe of cleaned data with borough as the index.
2. Group created dataframe by neighborhood and property type.
3. Calculate average price for each property type in each neighborhood of each borough, and sort results from highest to lowest.
4. Plot line graphs for each property type of the top five neighborhoods in each borough with the highest average prices of that property type.

#### Lowest Average Price

1. Create dataframe of cleaned data with borough as the index.
2. Group created dataframe by neighborhood and property type.
3. Calculate average price for each property type in each neighborhood of each borough, and sort results from lowest to highest.
4. Plot line graphs for each property type of the top five neighborhoods in each borough with the lowest average prices of that property type.

#### Lowest Average Minimum Night Requirement

1. Group cleaned data by borough and neighborhood, and filter by minimum night requirement.
2. Calculate average minimum night requirement for each neighborhood in each borough, and sort results from lowest to highest.
3. Plot line graph of top five neighborhoods in each borough with the lowest average minimum night requirements.





## Results



### New York City Level





### New York City Borough Level





### New York City Borough's Neigborhoods





## Trends/Observations/Conclusions

1. 