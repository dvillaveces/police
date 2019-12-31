# New York City Bike Lane Tickets by Police Precinct

Code originally in support of this post: ["Bicycle lane blocking in NYC"](https://dvillaveces.github.io/bike-lanes.html#bike-lanes)

This repo provides scripts to process, and analyze data for millions of traffic tickets in New York City by police precinct. Most of the [raw data](https://opendata.cityofnewyork.us/) comes from NYC Open Data.

## Instructions

##### 1. Run scrape.py

Used to gather all tweet_ids within a specified timeframe for an account (in this case [@Reported_NYC](https://twitter.com/reported_nyc))

From [@bpb27](https://github.com/bpb27/twitter_scraping)

##### 2. Download raw data

1. [Police Precincts](https://data.cityofnewyork.us/Public-Safety/Police-Precincts/78dh-3ptz)
2. [Bike lanes](https://data.cityofnewyork.us/Transportation/Bicycle-Routes/7vsa-caz7)
3. [Traffic violations](https://data.cityofnewyork.us/City-Government/Open-Parking-and-Camera-Violations/nc67-uf89)
4. [311 requests](https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9)

##### 3. Run Jupyter Notebook

`police.ipynb`

Or use that as a starting point to do your own analysis!

## Acknowledgements

- [bpb27](https://github.com/bpb27/twitter_scraping)
