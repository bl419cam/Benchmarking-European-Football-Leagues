# Benchmarking European Football Leagues

## Business Scenario
A South Korean online streaming startup is considering increasing its content offering to include live/replay of sporting events. Baseball and football(soccer) are the two most popular sports in South Korea, and since the most popular leagues of baseball and football are already covered by large incumbent media networks, the startup is looking to acquire rights to second tier European football leagues and the options are the following,

- Scottish Premier League
- Swiss Super League
- Liga Portugal
- (Eredivisie) Dutch Premier Division
- Belgian Jupiler Pro League
- Polish PKO Pro League

The startup wants to use a data-driven approach to evaluate the different leagues to see which one(s) would bring fans better entertainment value.

## Data Overview
Primary data source comes from Kaggle (https://www.kaggle.com/hugomathien/soccer) in the format of SQL database,

- 11 European Leagues
- span seasons 2008 to 2016
- over 25,000 match details
- over 10,000 player details
- player and team ratings from FIFA video game by EA Sports
- team formation data
- betting odds

## Approach
Use statistical methods, primarily AB hypothesis testing to compare metrics deemed relevant to entertainment value

- total goals scored per match
- number of scoreless matches per week
- average player ratings per match
- average player potential per match
