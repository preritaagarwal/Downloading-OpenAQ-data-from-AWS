# Downloading-OpenAQ-data
Python script for fetching Open AQ data from Resources on AWS

(link https://registry.opendata.aws/openaq/)

You can change the bucket name (for the directory you want to download the data from) as well as the dates.

Note -  It downloads gzipped ndjson files which then needs to be converted to csv or excel (I use a combination of bash and python routin eto unpack and soon add those 
routines here)

Credits for borrowing and modification of this code- 

https://patel-zeel.github.io/blog/data/openaq/2020/09/21/Programatically_download_OpenAQ_data.html#Setup
