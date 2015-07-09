# SI601_imdb_vs_moviedb
Created for SI 601 - Data Manipulation. Project compares IMDB ratings to MovieDB ratings for select movies.

imdb_top100 extracts the title and rating for the top 100 movies from IMDB using BeautifulSoup.

moviedb_top10 extracts information from the previously extracted 100 movies by connecting through the MovieDB API.

imdb_moviedb_comp writes a csv file containing the movie title, imdb rating, and moviedb rating.
