# Tweeter WeRateDog Data Wrangling Project
## by Vivian Wang



WeTweetDog is a popular twitter account about dog rating. It has a unique rating system include both numerator and denominator. It also comments dog in a humerous way that has over 4.8 millons followers. This popular account receives international coverage.

The datasets include pre-provided twitter achive data and image prediction data. Twitter API query was performed to get favorite and retweet count data. 

The project has two part:

-wrangle_act.ipynb notebook is to connect tweet API-tweepy,accessed and transformed the dataset. Then, created wrangle report in pdf format to identify and fixed 13 data quality and tidiness issues using Panda and Numpy

-act_report.ipynb notebook is to discover and visualize tweet trends over years using matplotlib and presented the key insights	from weRateDog traffic.


## Summary of Findings

> The final dataset after cleaning contains 2173 original tweets from 2015 Nov to 2017 Aug.With different dog stages, they receive average rating from 1 to 1.2. Among five dog stages, puppo and floofer got highest rating aroudn 1.2.

> Dogs with numerator rating of 13 or 14 normally receive higher retweet and favorite counts. When rating numerator is 0, it triggers high retweet and favorite. Users might be curious to find out why.

> The statistics also show that people tend to tweet more about dog ratings during winter season. The weather might not be good to walk dogs. People enjoy more to share their dog on social networks. In contrast, this tweet activity is lowest during nice summer time




