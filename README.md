# Craigslist-Rental-Data
Program to web scrape rental data from craigslist then used basic NLP to standardize the fuzzy neighborhood information

My first attempt at web scrapping and NLP. I scrapped rental data for the DC area from craigslist then used the NLP to help organize the neighborhood information. There were over 400 unique neighborhood descriptions, many of them seemingly the same (ex. Georgetown, Georgetow, geogeton, ...). I used the fuzzywuzzy package to then categorize these unique descriptors into their correct neighborhood name. 

I have 3 main files. The first one is the web scraping code. Then the data cleaning and NLP code. Finally some EDA of the final data. The EDA wasn't the focus of this project but it might be interesting to do more analysis in the future.
