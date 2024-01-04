# web-scrapping-for-movie

We will work with Web Scrapping,Data Combination,Data Formating,and then Data Analysis. Let's do this step by step, starting with data collection and ending with dilivery of Analyzed Data.

# ABOUT-MY-PROJECT

Welcome to the Movie Scrapping Project! This initiative is designed for extracting movie_related data from various websites. Dive into the world of movies by scrapping details such as:

1.movies_name

2.release_date

3.rating

4.duration

5.director_name

6.genre

====================================================================================================

The movie scrapping project employs python with the BeutifulSoup and requests libraries to systematically collect movie-related information from the movie database (TMDB). The script navigates through 50 pages of movie listing on TMDB, constructing URLs for each page. It then extracts data for individual movies, including details like movie_name,release_date,rating,director_name,duration and genre.

The script handles potential exceptions using try-except blocks.It employs nested scraping, first extracting links to individual movie pages and then retrieving specific details from each movie page.

The collected data is organized into dictionaries, one for each movie, and these dictionaries are append to the all_movie_data List. As with any web scrapping project, its essential to be mindful of ethical consideration and to comply with the terms of service of the targeted website. If you have more specific question or need further details feel free to ask!
