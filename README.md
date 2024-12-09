# Top 100 Movies of All Time Data Analysis

# Overview 
This project analyzes a dataset of the top 100 movies of all time. The dataset includes details such as rank, rating, genre, year, and title. The analysis focuses on cleaning the data, exploring trends in movie ratings, genres, and their distribution over time. Key insights include the distribution of movies by genre, ratings, and release years.

# Technologies Used
- Programming Language: Python
- Libraries: Pandas, Matplotlib, Seaborn
# Dataset
The dataset contains the following features:
- Rank: The movie's rank in the top 100 list.
- Rating: The user rating of the movie.
- Genre: The primary genre(s) of the movie.
- Year: The year the movie was released.
- Title: The title of the movie.
- Link: https://www.kaggle.com/datasets/shubhamoujlayan/top-100-movies-of-all-time
# Preprocessing Steps
Data Cleaning:
- Addressed missing or duplicate entries.
- Standardized genre names and handled movies with multiple genres.

Feature Engineering:
- Extracted specific time periods from release years for trend analysis.
## Exploratory Data Analysis (EDA)
Distribution by Ratings: 
- Visualized the distribution of movie ratings across all 100 entries.

Movies Per Year: 
- Examined the number of movies released per year and identified trends over time.

Genre Distribution: 
- Analyzed the count of movies by genre, identifying the most popular genres.

Ratings Over Time: 
- Investigated how movie ratings varied during specific time periods.

Genre vs. Rating:
- Explored how ratings differed across genres to identify top-rated genres.
# Results 
Ratings Distribution:
- Most movies in the dataset had ratings between 8.0 and 9.0, with very few falling below 7.5.

Movies Per Year:
- A significant concentration of movies was released during the 1990s and early 2000s.
- 1994 was the year with the most movie releases

Genre Distribution:
- Drama was the most represented genre, followed by Adventure.
- Crime and Sci-Fi consistently received higher average ratings compared to other genres.

# Future Improvements
- Incorporate additional features like box office earnings or director details for deeper insights.
- Develop a dashboard to make the analysis interactive and accessible to users.
