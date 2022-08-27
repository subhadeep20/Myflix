

A MOVIE RECOMMENDATION SYSTEM
•The webapp provides all the details of the requested movie such as overview, genre, date, rating, runtime, top cast etc. 
•The details of the movies(title, genre, runtime, rating, poster, reviews) are fetched using TMDB API. 
•Sentiment analysis is performed on the fetched reviews using nltk. An accuracy score of 98.77 is achieved. 
•Using the IMDB id, web scrapping is carried out to get the reviews of the user in the IMDB site using beautifulsoup4. •Recommends similar movies like OTT platforms using Levenshtein Distance based on review, votes, genre, overview etc. 
•Flask API is used to build up the application. Heroku cloud Platform as a Service is used to deploy and manage the webapp.