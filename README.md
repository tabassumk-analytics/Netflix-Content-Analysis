**Netflix Content Analysis & Cross-Platform Streaming Comparison**


**Project Goal**
With the explosion of streaming services, each platform competes to capture audience attention through content. This project explores the libraries of Netflix, Amazon Prime, Hulu, and Disney+ to understand their content strategies, genre preferences, audience focus (based on maturity ratings), and how these have evolved over time. The ultimate goal was to turn raw data into meaningful business insights that can inform content acquisition, user engagement, and platform positioning.

**Dataset Overview**

Used publicly available CSV files from Kaggle representing four major streaming platforms: Netflix, Amazon Prime, Hulu, and Disney+. Each dataset contained metadata for movies and TV shows including title, genre, release year, rating, and platform origin.

*Total Records-fter merging ~23,000 titles across all platforms
*Tools Used-Python, Pandas,Matplotlib & Seaborn,WordCloud,Scikit-learn and Jupyter Notebook.

**Netflix Analysis**

1.1 – Content Type Split
Netflix's catalog leans heavily toward movies. We confirmed this with a clean bar chart.
Netflix has more than double the number of Movies compared to TV Shows, suggesting a strong focus on film-based content. We confirmed this with a clean bar chart:

1.2 – Most Common Genres
We exploded genre tags and visualized the top 10 genres on Netflix.
Documentaries and International Dramas dominate Netflix’s genre mix, indicating an audience interested in real-life stories and globally diverse content.

1.3 – Maturity Ratings
A bar chart showing Netflix’s most frequent maturity ratings.
TV-MA is by far the most used rating on Netflix, showing a clear focus on adult-oriented content.

1.4 – Movie Duration Trends
Histogram showing typical Netflix movie length distribution.
Insight: Most movies fall in the 90–110 minute range, showing that Netflix tends to produce and license content of conventional film length.

1.5 – Season Count for Shows
Distribution of TV show season counts.
Insight: A large number of Netflix TV shows have just one season, indicating a preference for mini-series and short-run storytelling.

1.6 – Description Word Cloud
Frequent keywords in Netflix show descriptions.
Insight: Words like 'life', 'family', and 'love' frequently appear in show descriptions, suggesting a storytelling trend around emotional, personal themes.

1.7 – Predictive Modeling
We built a logistic regression model to predict whether a title is a Movie or TV Show based on features like rating, listed_in, and duration_int. The model achieved ~99.8% accuracy.


[![Netflix Content Type](netflix_content_type.png)](charts/netflix_content_type.png)  
[![Top Netflix Genres](netflix_top_genres.png)](netflix_top_genres.png)  
[![Netflix Rating Distribution](netflix_Rating_distribution.png)](netflix_Rating_distribution.png)  
[![Netflix Movie Durations](netflix_movie_durations.png)](netflix_movie_durations.png)  
[![Netflix TV Show Seasons](netflix_tv_show_seasons.png)](netflix_tv_show_seasons.png)  
[![Netflix Description Wordcloud](netflix_description_wordcloud.png)](netflix_description_wordcloud.png)  


**Cross-Platform Comparison**

2.1 – Content Volums

Total number of titles per platform.
Amazon Prime leads in overall content volume, followed by Netflix. Disney+ and Hulu have smaller, more curated libraries.

2.2 – Top Genres Across Platforms

The most frequently occurring genres overall.
Documentaries and Dramas dominate the genre landscape across all platforms, reflecting viewers' preferences for emotional and informative content.

2.3 – Movie vs TV Show Mix

Comparison of content type across platforms.
Netflix and Prime Video focus more on movies, while Hulu has a near-even mix. Disney+ leans toward TV series, driven by franchise spin-offs.

2.4 – Release Trends Over Time

Streaming content growth by release year.
There was a sharp increase in content releases post-2015, peaking around 2019–2020 during the streaming war and pandemic-driven demand.

2.5 – Rating Distribution

Raw rating frequency by platform.
Netflix leads with mature content (TV-MA), while Disney+ consistently avoids high-maturity content and sticks to PG and TV-G ratings.

2.6 – Cleaned Rating Distribution (Top 10)

Focussed on the top 10 rating categories across platforms.
When cleaned to show only the top ratings, Netflix and Hulu still lead in adult-rated titles. Disney+ remains strictly child and family-safe.

[![Platform Title Counts](platform_title_counts.png)](platform_title_counts.png)  
[![Top Genres All Platforms](top_genres_all_Platforms.png)](top_genres_all_Platforms.png)  
[![Platform Content Type Distribution](platform_content_type_distribution.png)](platform_content_type_distribution.png)  
[![Release Year Trend](release_year_trend.png)](release_year_trend.png)  
[![Raw Rating Distribution](Platform_rating_destriubtion.png)](Platform_rating_destriubtion.png)  
[![Top 10 Rating Categories](Platform_rating_distribution_top10.png)](Platform_rating_distribution_top10.png)  
[![Platform Genre Comparison](platform_genre_comparison.png)](platform_genre_comparison.png)


**Overall Business Insights**


Netflix is bold with its global and mature content, banking on variety and emotional connection.
Amazon Prime wins in content volume but lacks sharp genre focus. It may overwhelm rather than engage.
Disney+ is highly focused—family and kids rule here. It offers limited but on-brand content.
Hulu is the quiet all-rounder, balancing drama, comedy, and animation with consistent quality.
We also saw a market-wide surge in content volume since 2015, driven by competition, binge culture, and viewer demand for fresh, on-demand experiences.

**Recommendations**

Netflix should explore expanding its family and animated content to reach a broader base.
Amazon Prime could benefit from better categorization and content curation to enhance discoverability.
Disney+ may consider testing the waters with PG-13 or TV-14 rated shows to retain teen viewers.
Hulu should double down on exclusive content and surface its diverse library more prominently.
