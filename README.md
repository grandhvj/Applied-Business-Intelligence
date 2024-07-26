# Applied Business Intelligence

## Instructor: Tyler Woebkenberg

## Student

### Name: Varun Raj Grandhi
### Email: grandhvj@mail.uc.edu


## Repository Information
### Repository's URL: []()
### This is a private repository which is used to store all the codes related to course Applied Business Intelligence

# Final Peoject

## Overview

For my final assignment, I will gather my own data and conduct a detailed analysis using Power BI and Python. This is my opportunity to demonstrate the skills I've learned in handling, integrating, analyzing, and visualizing data with these tools. By combining these technologies, I aim to present comprehensive insights and compelling visualizations that showcase my proficiency.


## Task: Data Sourcing, Data Preperation, Data Integration, Data Anlysis and Data Visualization

### Step 1 

1) I have selected the data for my final Project from the Kaggle of the stock data [https://www.kaggle.com/datasets/equinxx/stock-tweets-for-sentiment-analysis-and-prediction]([https://www.kaggle.com/datasets/equinxx/stock-tweets-for-sentiment-analysis-and-prediction]) and the .csv file is downloaded by which I have done data sourcing.

2) Now the .csv file with date, Company name and the comments is loaded to jupyter notebook using pandas then processed with the nltk tool for the sentiment analysis. Using VADER which is proven to be great with the sentiment analysis in order to understand customers feelings towards products or brand. I applied this process to the selcted comapnies amazon and apple and drawn the sentiment score, neutral, negative and positive score.

3) Then I have integrated the new data points of the both the companies into one dataset and downloaded a .csv file and named as (sentiment_analysis_data.csv)

4) After the data is currated for the data analysis section, I start by conducting descriptive statistical analysis to get a better understanding of the sentiment scores of tweets about Amazon and Apple. This involves calculating various statistics like the mean, median, standard deviation, and the range of sentiment scores for each company. Next, I converted the date columns to datetime format, which helped me perform time-based analyses. Then I calculated daily and weekly average sentiment scores to observe how sentiment trends evolve over time for both companies. Additionally, I even analyzed the variability in sentiment scores and perform pairwise comparisons to highlight the differences in public sentiment between Amazon and Apple.

5) Then In the data visualization section, I created various plots to bring the sentiment analysis findings to life. I start by visualizing the average sentiment scores for each company using bar plots and pie charts to show the distribution of negative, neutral, and positive sentiments. Then depicted daily sentiment trends through line plots to illustrate how sentiment scores fluctuate over time. A heatmap is generated to visualize the daily average sentiment scores for each company, highlighting periods of high and low sentiment. Correlation heatmaps are used to examine relationships between different sentiment types (negative, neutral, positive). Finally, used line plots and box plots to compare sentiment trends and score distributions, providing a comprehensive view of public sentiment dynamics for Amazon and Apple.


## Task 2: PowerBI 

### README Document

#### Power BI Analysis Process

In this Power BI analysis project, I began by importing the sentiment analysis dataset, which included fields such as company name, date, sums of negative, neutral, and positive sentiments, sentiment score, stock name, and tweet text. The data was loaded from a CSV file into Power BI Desktop. After ensuring that each column had the correct data type and cleaning the data as necessary using the Power Query Editor, I created relationships between any relevant tables to enable comprehensive analysis. I then proceeded to create a variety of visualizations to explore and present the sentiment data effectively. On the Sentiment Overview page, I developed clustered column charts to compare the sums of negative, positive, and neutral sentiments by company, a line chart to display sentiment score trends over time, a pie chart to show the proportional distribution of sentiments, and another clustered column chart to summarize overall sentiment scores by company. On the Detailed Analysis page, I included a detailed table of all data points for in-depth analysis, a ribbon chart to visualize ranking changes of companies based on sentiment scores over time, and a scatter plot to map the relationship between positive and negative sentiments. These visualizations helped to reveal critical insights into public perception and sentiment trends for various companies.


## Task 3: FInal Report

I have documented all aspects of the data sourcing, data integration, data manipulation and analysis and visualization of the data even the Power BI analysis project in the final report, detailing the data import process, visualizations created, and insights gained from the sentiment analysis.


