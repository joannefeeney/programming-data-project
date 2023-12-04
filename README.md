# Programming for Data Analysis Project

### By Joanne Feeney

Data source: https://data.gov.ie/dataset/dublin-bonham-st-rainfall-data

***

For this project, I will synthesise the data contained in the above dataset. 

It consists of monthly rainfall records for a Met Éireann station at Bonham St. in Co. Dublin.

<img src="Rain_Cloud.png"  width="300" height="100">


The data contains 170 rows. (The first 13 being descriptors of the data)

There are 7 columns of data included in the data set:

* year - Year
* month - Month
* rain - Precipitation Amount (mm)
* gdf - Greatest daily fall (mm)
* rd - Number of rain days (0.2mm or more)
* wd - Number of wet days (1.0 mm or more)	
* ind - Indicator

I decided to chnage my dataset to this rainfall dataset at the last minute and so did not have enough time to complete this projectt as well as I could have.

I also made the mistake of spending too much time trying to figure out converting the year/month columns into time series and also too much time not realizing that most of my integer/float columns were being read in as strings and that is why some of my plots has not been appearing correctly.

What I was hoping to do with this dataset was to reference back to Met Éireann and their descriptors of weather in Ireland e.g.: https://www.met.ie/climate/climate-of-ireland

*"Ireland does not suffer from the extremes of temperature experienced by many other countries at similar latitude. Winters tend to be cool and windy, while summers, when the depression track is further north and depressions less deep, are mostly mild and less windy."*

I was hoping to compare rainfall over the course of the 12 years it was recorded in mm at this particlar station in Dublin from many years ago and see if it matched up to Met Éireanns assumptions of average Irish weather (year-round).

***
The End
