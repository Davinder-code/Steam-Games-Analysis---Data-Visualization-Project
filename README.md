## Steam Games Analysis — Data Visualization Project

CS-Data Visualizations class | Team Project

This project explores how price, genre, game mode, and free vs. paid status impact user reviews on Steam. 
Using datasets from Kaggle, my team cleaned, filtered, and visualized the top reviewed Steam games to identify patterns in game popularity and user satisfaction.
Our analysis and results are fully supported by the report and poster included in this repository.

## Goals & Research Questions

As outlined in the project report, we focused on:

How do price, genre, and single-player vs. multiplayer influence review scores?

Do free games perform differently than paid games?

What factors are most strongly associated with positive reviews?

## Data Collection & Cleaning

The dataset originally contained 100,000+ observations and 21 columns.
We filtered the data to focus on the top 50 reviewed free games and top 50 reviewed paid games, 
then combined them into a clean dataset of 98 observations and 14 relevant variables such as:

Name

Genre

Total reviews

Review score

Positive/negative totals

Price

Multiplayer support

We processed the data in R, cleaned missing values, removed duplicates, and built new combined data frames.

## Visualizations Created

Three core visuals were developed, each chosen for clarity and insight:

1. Total Positive Reviews by Genre (Free vs Paid)

Grouped bar chart comparing genres; paid games had higher positive totals across almost every genre.


2. Top 10 Most Reviewed Steam Games

Horizontal bar chart showing major titles like Counter-Strike 2, GTA V, Cyberpunk 2077, Terraria, and more.


3. Price vs Review Score

Scatter plot showing a clear downward trend: as price increases, review score expectations also rise.


## Key Findings

Based on our analysis:

Paid games dominate positive reviews and total review counts.

Moderately priced games ($10–$40) tend to achieve the highest scores.

Free games thrive mainly in multiplayer-focused genres (e.g., shooters, battle royale).

Price does not guarantee high review scores—game experience matters more.

## What I Contributed

My work on this team project included:

Data cleaning and restructuring in R

Helping generate visualizations

Writing parts of the report

Interpreting visual findings

Assisting with the final poster and project summary

## Skills Demonstrated

Data Visualization

R Programming (tidyverse, ggplot2)

Data Cleaning & Transformation

Statistical Interpretation

Team Collaboration & Report Writing
