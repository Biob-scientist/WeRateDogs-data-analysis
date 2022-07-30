# Project: Wrangling, Analyzing, and Visualizing WeRateDogs data
## by Oluwasola Aduewa
***
## Overview
***
> The main objective of this project is to wrangle WeRateDogs Twitter data to create interesting and trustworthy analyses and visualizations. WeRateDogs is a popular Twitter account that has over 9 million followers and as the name implies- it rates dogs

>This project comprises three central aspects:

>- Data gathering from different sources which also come in different file formats
>- Data cleaning at its best, addressing quality and tidiness issues associated with the data.
>- Analysis and visualization of insights from the cleaned data.

# Data Wrangling
***
## Data Gathering
> Three main datasets were collected from different sources to complete the project and they are:

>- The Enhanced Twitter archive data, compiled by @dogrates and shared with Udacity. This archive contains basic tweet data for all 5000+ of their tweets, as of August 2017. Udacity provided this file, so it was treated as a file on hand.
>- An Image predictions tsv file, compiled by running every image in the WeRateDogs Twitter archive through a neural network that can classify breeds of dogs. The file was downloaded programmatically from Udacity servers, using the requests library.
>- Additional data for each tweet in the archive (retweet count, favorite count, and hashtags) was pulled from the Twitter API using the Tweepy library. API using the Tweepy library.
## Assessing Data
>The datasets were assessed both visually through jupyter lab and by programmatic means using pandas and NumPy. Both data quality and tidiness issues were assessed and documented for the later process- data cleaning.
### Data Cleaning
> Each of the data tidiness and quality issues discovered in the previous stage was cleaned for hassle-free data analysis. The data wrangling report, `wrangling_report.pdf` concisely highlights the data cleaning process.

## Concentration
***
>- Analyze WeRateDogs Twitter presence progression
>- Understanding the uniqueness of the WeRateDogs rating system
>- How frequently does one dog stage get posted compared to others
>- Popularity of dogs breeds that featured in posts
>- How users interact with tweets that relate to various dog stages.
>- Hashtags and how they relate to user engagement.

## Summary of Findings
***
>- There's a strong positive relationship (0.93) between the number f retweets and favorites
>- Even though the rating system does not agree with Math theories, the WeRateDogs system could be seen as pyramidal just like every other rating system.
>- Of all the dog stages, Puppers featured the most in all posts
>- It was also found that the handle rarely uses hashtags to engage the public. however, #WomensMarch protest and #ScienceMarch rally gathered the most media engagements

> Full report of the analysis detailing the insights uncovered is contained in the `act_report.pdf`

### Python Libraries used
>__pandas, NumPy, requests, BeautifulSoup, tweepy,json__