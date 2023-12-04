# Programming for Data Analysis Project

### By Joanne Feeney

Data source: https://data.gov.ie/dataset/dublin-bonham-st-rainfall-data

***

For this project, I will synthesise the data contained in the above dataset. 

It consists of monthly rainfall records for a Met Éireann station at Bonham St. in Co. Dublin.

<img src="Rain_Cloud.png"  width="600" height="300">


The data contains 170 rows. (The first 13 being descriptors of the data)

There are 7 columns of data included in the data set:

* year - Year
* month - Month
* rain - Precipitation Amount (mm)
* gdf - Greatest daily fall (mm)
* rd - Number of rain days (0.2mm or more)
* wd - Number of wet days (1.0 mm or more)	
* ind - Indicator

I decided to change my dataset to this rainfall dataset at the last minute and so did not have enough time to complete this project as well as I could have.

I also made the mistake of spending too much time trying to figure out converting the year/month columns into time series and also too much time not realizing that most of what sould have been my integer/float columns were being read in as strings and that is why some of my plots has not been appearing correctly.

What I was hoping to do with this dataset was to reference back to Met Éireann and their descriptors of weather in Ireland e.g.: https://www.met.ie/climate/climate-of-ireland

*"Ireland does not suffer from the extremes of temperature experienced by many other countries at similar latitude. Winters tend to be cool and windy, while summers, when the depression track is further north and depressions less deep, are mostly mild and less windy."*

I was hoping to compare rainfall over the course of the 12 years it was recorded in mm at this particlar station in Dublin from many years ago and see if it matched up to Met Éireanns assumptions of average Irish weather (year-round).

What I have been able to present is a notebook that reads in the dataset, skipping the first 13 lines of information. 
I attempted to drop the empty sections of the dataset and then change the type to int/float etc but unfortunately I was unsuccessful.
You can see via a value sorted table which years had the greatest daily fall in mm each year (top 20)
Next we have a pie chart of the years the count was active at this weather station.

I sliced the data to differentiate between the different years and assigned abbreviated month names to the 1-12 that represented months in the data.
There is a plot of the annual rainfall in mm from 1942 to 1954.
There are scatter plots of data from teh first year the rainfall was recorded and the last year.

I have a histogram of the greatest daily fall of rain grouped by how many times it appers in the dataset which shows us that most months over the 12 years have a unique amount of rain recorded.

I then have some bar plots of the first and last year on record.

Unfortunately I have not completed this project as well as could be but am hoping with some feedback from you I can learn better ways of dropping empty data and re-assigning strings to float etc.

***
The End
