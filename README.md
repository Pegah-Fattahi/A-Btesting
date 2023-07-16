# A/B Testing Based on Unique Page Views
## Introduction
This project aims to reassess the efficacy of two distinct marketing campaigns, "NewYear" and "BlackFriday", through a unique approach. Following concerns about the reliability of the original click tracking data, we propose to estimate the number of users who clicked on campaign banners based on unique page views data, rather than traditional click counts.
Our approach joins the original marketing campaigns data from the turing_data_analytics.adsense_monthly table with the website tracking data from the turing_data_analytics.raw_events table. The 'clicks' from the original data will be replaced with our new estimate - the number of unique users brought to the website by these marketing campaigns.

## Task Requirements
The task involves crafting an SQL query to extract all necessary data, and then conducting an A/B test to estimate whether different variants of the marketing campaigns (V1 vs V2) for both "NewYear" and "BlackFriday" had significantly better clickthrough rates. The clickthrough rates will be estimated as the number of users who clicked on the campaign divided by the number of impressions.
We will ignore the timing of user tracking data, i.e., we will not check if the sessions were recorded when the marketing campaign was running.
The A/B testing will be performed on the results from the SQL query. While we will make use of a Binomial A/B test Calculator, bonus points are awarded for creating custom A/B testing for this exercise.
The project will include visualizations to help illustrate the A/B testing results, making it easier to interpret the outcomes of our analysis.

## Technologies
This project will utilize:

SQL: For data extraction and manipulation.

Explore the project files for more in-depth understanding of the methodologies used and feel free to provide feedback or ask questions. Happy browsing!
