# Python_FBI_Dataset

The FBI crime data set make it possible to analyzing time series data and see changes in crime rates over a 20 years period or geographically.
Data set over a 20 years period is avaiable here: 
https://ucr.fbi.gov/crime-in-the-u.s/2013/crime-in-the-u.s.-2013/tables/1tabledatadecoverviewpdf/table_1_crime_in_the_united_states_by_volume_and_rate_per_100000_inhabitants_1994-2013.xls/output.xls

Data set for geographically statistics is avaiable here:
https://ucr.fbi.gov/crime-in-the-u.s/2013/crime-in-the-u.s.-2013/tables/table-8/table_8_offenses_known_to_law_enforcement_by_state_by_city_2013.xls

Questions:
1. Has the crime decreased or increased over the last 20 years?
2. Has the type of crime changed?
3. Has the crime moved to from one area to another?
4. Is there a connection between type of crimes and locations?
5. Which year was the most crime and what crime occured most times?


Our solution (We have completed this so far)

- Download Excel:
We have imported webget to get the URL with the dataset.
First we got a forbidden error 403, we solved that with an useragent-header.

- Load Excel to Python
We have used Pandas module to load the Excel-file into a Dataframe.

- We print the specific tabel with the statistic over crimes between 1994-2013

- We print specific row (1994, 2004, 2013)

- Manuelt we have found a way to add all the amount of the crimes for a specific row (a hack way).
We need help to do it right!!!!!






