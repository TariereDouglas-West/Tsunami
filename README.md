# Tsunami

DATA WRANGLING/DATA CLEANING

Tsunami Data from Kaggle

Curiosity on natural disaster shows a reason to demonstrate my ability to work on wrongly formatted variables (mostly date and time) to get a well-structured dataset that will pose no errors during the analysis process.

Tsunami Events dataset downloaded from Kaggle. This dataset includes a record of the year, tsunami event validity (indicates the likelihood that the given event was a tsunami ranked from 1-4 with 1 being that it was not really a tsunami and 4 indicates that it was a definite tsunami), It includes data on the date, time, location, and magnitude of each event, as well as information on the impact of the tsunami, such as the number of deaths and injuries. The dataset is also enriched with additional information, such as bathymetry data, which can be used to model the propagation of tsunami waves from 1900 – 2023.

•	Contains information on over 2,000 tsunami events from around the world
•	46 columns & 1,443 rows


Before uploading the dataset into MySQL workbench, I scanned through the data to ensure nothing looked amiss. I was able to find that some cells did not have any value. Not to worry this will be solved in MySQL.

The steps I took for this data wrangling project in MySQL includes Data Discovery, Data structuring, checking and handling data entry inconsistency/irregularities, handling blank values, checking for duplicates and so on.

DATA DISCOVERY:

A glance at my dataset, shows that it contains date, time, text, blank values and some numerical values.
To make it better organized for easier consumption and analysis, I checked the format/datatypes of the various variables as to configure each of them so they can be understood and examined to find patterns and trends during analysis.


 In the data set the date is broken down into year, day, month and the time is broken into columns as hour, minutes, seconds. These need to be parsed and combined.

