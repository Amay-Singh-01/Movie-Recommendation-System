# Moviella - A Content Based Recommendation System

The details of the movies(title, genre, runtime, rating, poster, etc) are fetched using an API by TMDB, https://www.themoviedb.org/documentation/api, using the IMDB id of the movie as input to the API.

## How to generate the API key?

Create an account on https://www.themoviedb.org/, click on the `API` link in your account settings and fill the required details to apply for API key (fill "NA" under the application URL column". After completing this process your API pin will be generated and displayed on the screen.

## How to run the project?

1. Clone or download this repository to your local machine.
2. Install all the libraries mentioned in the [requirements.txt] file in the same directory. Also, download the       datasets in .gitignore file and paste them in the project folder.
3. Geneate your API key from https://www.themoviedb.org/ and replace in the javascipt file: "recommend.js".
4. Open command prompt in your project directory and run the file `main.py`.
5. Go to this address in your browser : "http://127.0.0.1:5000/"

## Sources of the datasets 

1. IMDB 5000 Movie Dataset - (https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset)
2. The Movies Dataset - (https://www.kaggle.com/rounakbanik/the-movies-dataset)