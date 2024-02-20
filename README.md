# (Ford Go Bike System Data )
## Table of Contents
1. Introduction
2. List of libraries used
3. Files in repository
4. Summary of Findings
5. Key insights for presentation


### Introduction
This data set includes information about 183412 individual rides made in a bike-sharing system covering the greater San Francisco Bay area. The dataset originally contains 183412 rows and 16 columns. After wrangling and cleaning the dataset,it now contains 174952 rows and 24 columns.The columns include start time,start station and their coordinates,end time,end station and their coordinates,bike id,user type etc.

### List of libraries used
1. Numpy
2. Pandas
3. Matplolib
4. Seaborn

### Files in repository
1. bikedata.csv.zip : This file contains the dataset required for our project.
2. Part_I_Bikedata_analysis_exploratory.ipynb: This contains python code for performing data wrangling.
3. Part_II_Bikedata_analysis_explanatory.ipynb: This contains python code for performing data visualisation.
4. Part_II_Bikedata_analysis_explanatory.slides.html: This contains 3 visualisations to convey key insights along with descriptive comments.
   
### Summary of Findings

The dataset contains data for months of February and March '19.

The average duration of the trip is 500sec.

Most number of the trips happened on weekends rather than on weekdays.

The 8th,9th,17th and 18th hours have the highest number of trips. The 3rd,4th trips have the least number of trips. 

Most of the bike rides are done by 20 to 40 years old people and they have got many outliers with the highest one being >140 years old.

The duration of trip had a negative relation with age.

The duration of trip in terms of gender:other>female>male.

The duration of trip in terms of days:weekends>weakdays.

The duration of trip in terms of user type:customer>subscriber.

### Key Insights for Presentation

1. There are high number of rides during the opening office hours and closing office hours.

2. Though the number of higher duration trips is more for male riders but time of duration is higher for women and others.

3. Customers travel longer distances though the number of trips are only 10% of subscribers.

