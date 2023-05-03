# US-Accidents-EDA
This is a project to perform exploratory data analysis (EDA) on the US accidents dataset. The dataset contains *2.8 million accident records* across the US, with 47 different features. The aim of this project is to analyze three columns - cities, start time, start latitude, and longitude - to gain insights into the factors contributing to accidents and their impact.

## Dataset
The US accidents dataset is available on [Kaggle](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents). It is a large dataset that contains information about accidents reported in the US from February 2016 to December 2021.

## Tools Used
The following libraries and tools were used for this project:

- Matplotlib
- Seaborn
- Pandas
- opendataset
- Folium
## Analysis
The analysis performed on the US accidents dataset provided the following insights:

- There is data about 11628 cities.
- Miami has the highest number of accidents (106966), followed by Los Angeles (68956), Orlando (54691), Dallas (41979) and Houston (39448).
- No data for New York, even though it is the most populous city in US.
- There are over 1110 cities with exactly one accident reported.
- Less than 5% cities (494) have more than 1000 number of accidents.
- More than 95% cities (11187) have 1000 and less than 1000 number of accidents.
- 2021 has the highest number of accidents reported (1511745).
- On an average, High Percentage of accidents occur between 1 PM to 5 PM.
- Weekdays have more accident reports than weekends.
- On weekdays the trend of number of accidents has two maximas (7AM to 9AM) and (3PM to 5PM).
- On weekends between 12 PM and 6 PM, there are more accident reports.
- More number of accidents occur in winters.
- There is some missing data for the year 2016.
- In 2017, there are more number of accidents in the starting of the year.
- In 2020, data for a month is either missing or that month has 0 number of accidents reported. This maybe due to the COVID-19 quarantine.  

## Acknowledgements
The US accidents dataset is available on [Kaggle](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents). Special thanks to Sobhan Moosavi, Mohammad Hossein Samavatian, and Srinivasan Parthasarathy for making this dataset publicly available.





