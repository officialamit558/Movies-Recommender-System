# **Building And Deploying A Movies Recommender System**

Content Based Recommender System recommends movies similar to the movie user likes and analyses the sentiments on the reviews given by the user for that movie.

The details of the movies(title, genre, runtime, rating, poster, etc) are fetched using an API by TMDB, https://www.themoviedb.org/documentation/api, and using the IMDB id of the movie in the API. 

We use *web scraping* to get the reviews given by the user in the IMDB site using beautifulsoup4 and performed sentiment analysis on those reviews.
## Running Flask Tests

To run a Flask deployment tests, run the following command

```bash
  python main.py
```

// static/Screenshot (259).png

![logo](static/Screenshot (259).png "Search Movie")

## Running Heroku Tests

To run a Heroku deployment tests, click on the following link:

[Netflix Recommender System App](https://netflixrecommenderapp.herokuapp.com/)


## Deployment

### Steps To Deploy The App:

Prepare your dataset:

        1. Data Extraction
        2. Exploratory Data Analysis(EDA)
        3. Feature Engineering
        4. Model Building and Tuning
        5. Building Flask API
        6. Pushing code to Github
        7. Connecting to your Heroku account 
        8. Deploy App


## Demo

[Click HERE To View App](https://moviesrecommenderapp.herokuapp.com/)



![logo](https://github.com/MrBriit/Netflix-Recommender-System-and-Deployment/blob/main/net%20screenshot.png?raw=true)

