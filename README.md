# US Census data for all countries and US states 

## US and Worldwide Census data
Since the raw data is pulled from us census data through the script in the file
scripts/census.py using the api https://api.census.gov/data/timeseries/idb/1year ( The api could be visited for checking the upates that take place on a yearly bases, nothing in census is refreshed less than that). The current files referenced are "SCPRC-EST2019-18+POP-RES.csv" for US states and "pop.csv" for worldwide countries

## Census data for provinces in Canada, China, and Australia
Data are found in Census/Final. The census are retrieved manually (as they did not have API). 

|Column No.|Country|Comments|link|
|---|---|---|---|
|0|China| National Bureau of Statistics of China.Did not have male to female ratio only have ration at birth for a certain year (2000)|http://data.stats.gov.cn/english/easyquery.htm?cn=E0103References|
|1|Canada|Statistics Canada|https://www12.statcan.gc.ca/|
|2|Australia|Australian bureau of Statistics|https://www.abs.gov.au/|

## Mergin all togehter
Merging all together is found in Census/Final/all.csv (It is done manually as well)
