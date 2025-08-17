📊 Netflix Data Analysis

This project analyzes a Netflix dataset containing movie details and applies Exploratory Data Analysis (EDA) and Regression Modeling to understand what influences movie ratings.

📂 Dataset

The dataset includes the following features:

Release_Date – Date when the movie was released

Title – Name of the movie

Overview – Short description of the movie

Popularity – Popularity score

Vote_Count – Number of audience votes

Vote_Average – Average rating given by viewers

Original_Language – Language of release

Genre – Movie genres

Poster_URL – Movie poster link

🔍 Exploratory Data Analysis (EDA)

Distribution of movies across years and genres

Identification of most popular genres

Trends in popularity scores over time

Relationship between vote count and ratings

📈 Visualizations were created to highlight patterns in release trends and genre distributions.

📈 Regression Analysis

A Linear Regression model was developed to predict a movie’s average rating (Vote_Average) based on:

Popularity

Vote Count

Genre

Release Year

Key Results:

Popularity and vote count are strong predictors of higher ratings.

Genre has an impact but is less influential compared to popularity.

Recent movies generally attract higher popularity scores.

🎬 Recommendation System

Content-based recommendation system using TuriCreate

Recommendation from Overview (text similarity)

Recommendation from Genres (categorical similarity)

Combined approach: overview + genre features

Use regression insights to recommend content that aligns with viewer preferences.

🛠️ Tools & Libraries

Python 3

Pandas, NumPy → Data cleaning & analysis

Matplotlib, Seaborn → Data visualization

Scikit-learn → Regression modeling

TuriCreate → Recommendation system
