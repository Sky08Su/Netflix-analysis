# Netflix-analysis

The purpose of this analysis is to explore shows and movies in Netflix, including duration, rating, cast, director and etc. 

1. examine data, remove nan, extract data
- use .info() to understand the dataset and see how much data is missing in each column
- remove missing value in added_date, extract year and month to 2 new columns. Please note that there are quite some missing data in certain columns. In order to avoid removing too much data, I only removed a few and will continue doing so when analysing specific columns. 
- drop irrelevant columns
- check duplicated data
- split dataset into two categories - TV show and movie, for further analysis

2. Explore data

Movies:
- compare the number of two categories
- use heatmap to demostrate newly added movies
- groupby monthly data and use line chart to show least added movie months
- use barchart to demonstrate movies by country (use dict.get() and dict to dataframe to prepare data)
- analyse movie ratings and assume its main audience
- distribution of duration
- find out which director has most movies in Netflix

TV shows:
- use heatmap to demostrate newly added TV shows
- groupby monthly data and use line chart to show least added TV shows months
- use barchart to demonstrate data by country (use dict.get() and dict to dataframe to prepare data)
- analyse ratings and compare it with movies
- distribution of duration
- find out which actor/actress has most TV shows in Netflix
