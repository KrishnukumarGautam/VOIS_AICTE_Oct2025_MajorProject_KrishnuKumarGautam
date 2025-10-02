📺 Netflix Content Trends Analysis

Overview
This project provides a comprehensive analysis of Netflix’s content catalog to uncover trends in Movies vs TV Shows, popular genres, and country-wise contributions. The analysis aims to provide data-driven insights to guide strategic decisions for content acquisition and production.

🎯 Problem Statement

Netflix is a global streaming giant with an ever-growing library of Movies and TV Shows. With rising competition from platforms like Amazon Prime, Disney+, and regional OTT providers, it’s crucial to understand how content distribution has evolved over time.

Objective:

Analyze Netflix’s content trends to identify:

Balance between Movies and TV Shows

Popular and underrepresented genres

Country-wise content contributions

🔍 Importance

Understanding these trends helps Netflix:

Make strategic content acquisition and production decisions

Identify top-performing genres and categories

Expand its global reach while catering to regional audience preferences

📝 Dataset

Source: Netflix Dataset (CSV)

Records: 7,789+

Columns: 11 (Title, Director, Cast, Country, Date Added, Release Year, Rating, Duration, Type, Genre, etc.)

Time Span: 2008 – 2021

Key Columns Used for Analysis:

type → Movie / TV Show

listed_in / genre → Genre categories

country → Country of origin

date_added & release_year → Year of addition for trend analysis

📊 Analysis Objectives

Distribution of Movies vs TV Shows over the years.

Popularity trends of top genres.

Country-wise contribution trends.

🖥️ Tools & Technologies

Python 3.x.

Libraries: pandas, numpy, matplotlib, seaborn, plotly.

Environment: Google Colab (supports file upload/download and inline plotting).

📈 Plots & Insights

Movies vs TV Shows Trend

Visualizes the number of Movies and TV Shows added each year

Identifies growth patterns in content type over time

Top Genres Trend

Tracks popularity of top genres (Drama, Comedy, Thriller, etc.)

Helps understand evolving audience preferences

Country-wise Contribution

Displays content contributions from top countries (USA, India, UK, etc.)

Highlights regions with the most content production

⚠️ Plots are adaptive — they work even if dataset column names or values differ.

✅ Key Findings

Most Netflix content comes from the USA, India, and the UK

Drama, Comedy, and Thriller are consistently top genres

The number of TV Shows has been increasing faster than Movies in recent years

Regional content is growing, showing Netflix’s focus on global expansion

💡 Strategic Recommendations

Strengthen high-demand genres (Drama, Comedy, Thriller)

Invest in underrepresented genres (Documentary, Animation)

Maintain a balanced production of Movies vs TV Shows

Expand region-specific content (India, South Korea, Latin America)

Enhance global reach with subtitles/dubbing

Leverage data-driven decisions using engagement metrics

Experiment with innovative formats (interactive content, short-form series)

⚙️ How to Use

Upload the Netflix CSV dataset to Colab

Run the provided Python script

View inline plots and download cleaned dataset (netflix_cleaned.csv)

Explore the plots/ folder for all saved visualizations

🔗 Project Structure

Netflix-Content-Trends-Analysis/
├─ netflix_analysis.ipynb        # Main Colab notebook
├─ netflix_cleaned.csv           # Cleaned dataset (after execution)
├─ plots/                        # Folder containing all generated plots
│   ├─ movies_vs_tvshows.png
│   ├─ top_genres_trend.png
│   └─ top_countries_trend.png
└─ README.md                     # Project documentation

📌 Notes

Script adapts to variations in column names or dataset inconsistencies

Plots will always render based on available data

Cleaned dataset is saved automatically for further analysis

📚 References

Netflix Dataset (CSV)

Python Libraries: pandas, matplotlib, seaborn, plotly

Google Colab Documentation:
