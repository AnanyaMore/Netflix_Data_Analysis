# Netflix_Data_Analysis
# Netflix Data Analysis Project

## Overview
This project performs a series of SQL queries on the Netflix dataset to answer 15 business questions related to movies and TV shows. The analysis includes counting content types, identifying popular genres, top actors, and more.

## Dataset
The dataset contains the following columns:

- `show_id`: Unique ID for each show
- `type`: Movie or TV Show
- `title`: Name of the show
- `director`
- `casts`
- `country`
- `date_added`
- `release_year`
- `rating`
- `duration`
- `listed_in`: Genre/categories
- `description`

## SQL Queries
The SQL script (`netflix_project.sql`) includes queries for:

1. Counting the number of Movies vs TV Shows
2. Most common rating per type
3. Movies released in a specific year
4. Top 5 countries with the most content
5. Longest movie
6. Content added in the last 5 years
7. Movies/TV shows by a specific director
8. TV shows with more than 5 seasons
9. Count of content in each genre
10. Average content released per year in India
11. Movies that are documentaries
12. Content without a director
13. Movies featuring a specific actor in the last 10 years
14. Top actors in Indian movies
15. Categorization based on 'kill' and 'violence' in descriptions

## How to Run
1. Open your SQL client (e.g., PostgreSQL, MySQL).
2. Create a database and table using `netflix_project.sql`.
3. Run the queries one by one to see the results.

