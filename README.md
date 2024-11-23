# **Building And Deploying A Movies Recommender System**

Content Based Recommender System recommends movies similar to the movie user likes and analyses the sentiments on the reviews given by the user for that movie.

The details of the movies(title, genre, runtime, rating, poster, etc) are fetched using an API by TMDB, https://www.themoviedb.org/documentation/api, and using the IMDB id of the movie in the API. 

We use *web scraping* to get the reviews given by the user in the IMDB site using beautifulsoup4 and performed sentiment analysis on those reviews.

This project implements a Movie Recommendation System using Natural Language Processing (NLP) and collaborative filtering approaches. Below is the directory structure, installation guide, and feature overview.

```plaintext
Movie_Recommendation_System/
├── statics/
│   ├── autocomplete.js
│   ├── image.jpg
│   ├── loader.gif
│   ├── recommended.js
│   └── style.css
├── templates/
│   ├── home.html
│   └── recommended.html
├── .gitignore
├── data1.csv
├── finaldata.csv
├── main_data.csv
├── main.py
├── movies_metadata.csv
├── newdata.csv
├── NLP_model.pkl
├── Procfile
├── requirements.txt
└── transformer.pkl

## Installation and Setup
1. Clone the repository:

git clone https://github.com/your-username/Movie_Recommendation_System.git


2. Navigate to the project directory:

cd Movie_Recommendation_System


3. Install dependencies:

pip install -r requirements.txt


4. Run the application:

python main.py


5. Open your web browser and go to:

http://localhost:5000



Features

Movie Recommendations: Get personalized movie recommendations based on user input.

Autocomplete Functionality: Real-time search suggestions powered by autocomplete.js.

Interactive Web Interface: User-friendly UI built with HTML, CSS, and JavaScript.

Preprocessed Data: Datasets and models are preloaded for efficient recommendations.


File Descriptions

statics/: Contains static assets like JavaScript, CSS, images, and loaders.

autocomplete.js: Script for search autocomplete functionality.

style.css: CSS file for styling the web application.

loader.gif: Loading animation.

recommended.js: Handles movie





```bash
  python main.py
```

![logo](https://github.com/officialamit558/Movies-Recommender-System/blob/main/static/Screenshot%20(259).png)
![logo](https://github.com/officialamit558/Movies-Recommender-System/blob/main/static/Screenshot%20(260).png)
![logo](https://github.com/officialamit558/Movies-Recommender-System/blob/main/static/Screenshot%20(261).png)
![logo](https://github.com/officialamit558/Movies-Recommender-System/blob/main/static/Screenshot%20(262).png)

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


