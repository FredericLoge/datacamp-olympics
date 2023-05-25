# Datacamp - Olympic Games 🥇 🥈 🥉

This repository contains the data on Olympics.
In the `data/` folder there are two Comma Separated Values (CSV) files, `athlete_events.csv` and  `noc_regions.csv`.

## Part 1: preliminary data inspection, simple questions

The first part of the datacamp is a fixed list of questions you should answer, in order to reproduce the basic first steps of dataset inspection.
- load each csv file in a pandas DataFrame
- briefly inspect each dataset: which information do they hold?
- combine the information from both dataframes into a single one, using `pd.merge` based on their common column. Delete the two old dataframes. In the new dataframe, drop the `NOC` and `notes` columns.
- how many lines are there in the main dataset? Is this size problematic?
- what is the time range of the data?
- how many distinct athletes are in the dataset?
- what is the proportion of missing values in the Height column?
- how many distinct Events are covered? which ones have been
- what is the repartition of the number of participations per athlete?
- which event has the youngest participants on average? and the tallest?
- how many athletes have an homonym in the dataset? which names correspond to the highest number of distinct athletes?

## Part 2: summarizing answers to questions with graphs
Based on this data, many questions can be answered, here are a few examples:
- Dominating countries. Which countries dominate the OG currently? thanks to which events? how has this evolved throughout the years? which have the largest rate of success compared to their participation numbers?
- Winning strategies. Which attribute is the most correlated to performance? country, age, height, weight? an analysis targetted on Athletics events
- Participants morphology. How has the morphology of skiiers changed throughout the years? Does is seem related to performance? Breakdown by events.
- Sports availability. When did Judo events start for men & women? Is there other sports with similar disparities? Is there any sports that were once in the Olympics and now disappeared?

Your task, should you choose to accept it, is to investigate in depth a question using descriptive statistics, data visualization, clustering and dimension reduction. You will be working in a group of 3 or 4, and we will help you along all day. The question can be one of the above suggestions, but we highly encourage you to find one you have a high interest in amongst yourselves :rocket:
