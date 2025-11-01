# Netflix Content Analysis
This repository contains a Jupyter Notebook (Netflix_analysis.ipynb) that performs an exploratory data analysis (EDA) on the Netflix shows and movies dataset. The analysis aims to uncover insights into content strategy, user demographics, popular genres, and production trends.

📊 Project Overview
The analysis involves several key steps:

Data Loading: The dataset is loaded from netflix.csv.

Data Cleaning: Preprocessing steps include handling missing values (dropping or filling with the mode), removing duplicates, and converting data types (like date_added to datetime).

Feature Engineering: New columns such as year_added and month_added are extracted to facilitate time-based analysis.

Exploratory Data Analysis (EDA): The core of the notebook, where visualisations are generated to answer specific questions about the Netflix library.

📈 Key Analyses Performed
The EDA section is broken down into several key areas of investigation:

Content Strategy
Movie vs. TV Show: Visualisation of the content split between movies and TV shows.

Popular Genres: Identification and plotting of the top 10 most common genres on the platform.

Content Over Time: A line plot showing the trend of content being added to Netflix over the years.

Geographic Distribution: Analysis of the top 10 countries that produce the most content.

User Demographics & Targeting
Frequent Ratings: A bar chart of the most common content ratings (e.g., TV-MA, PG-13).

Mature Content: A specific look at the top 10 countries producing "TV-MA" (Mature Audience) content.

Detailed Breakdowns
Genre Analysis: Separate plots for the top 10 most popular genres for Movies and TV Shows.

Geographic Analysis: A comparison of the top 10 genres produced in the United States versus all other countries combined.

Recent Trends: Analysis of the top 10 genres from content added in the last three years.

Talent & Engagement
Top Directors: Identification of the top 10 directors with the most content on the platform.

Top Actors: Identification of the top 10 most frequently appearing actors.

Content Duration:

Calculation of the average movie duration (approx. 103 minutes).

Calculation of the average TV show duration (approx. 1.9 seasons).

A line plot showing the trend of average movie duration by release year.

Visualization
Word Cloud: A word cloud is generated from movie titles to visualise the most common words in titles.

🛠️ Libraries Used
This analysis utilises the following Python libraries:

pandas: For data manipulation and analysis.

seaborn: For statistical data visualisation.

matplotlib.pyplot: For creating plots and charts.

wordcloud: For generating the title word cloud.
