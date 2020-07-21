# Sci-Fi or Fantasy Project Data
This repo holds just the data for the sci-fi and fantasy data mining project.

- The main project is at https://github.com/hightechu/data-mining-template, but due to the large size of the data set it prevents the whole project from being forked as a template and therefore is kept seperately in this repository.
- The original data se can be found here: https://www.kaggle.com/stefanoleone992/imdb-extensive-dataset
- movie_descriptions.csv is processed data which contains only the descriptions of movies of the Sci-Fi and Fantasy genres from the original data set in a document term matrix (DTM) form that can be used for text classification
  - An example of a simple DTM:
  ![Screen Shot 2020-07-20 at 4 21 25 PM](https://user-images.githubusercontent.com/45152371/87995705-14775180-caa5-11ea-9508-4b09b8369274.png)
- movie_genres.csv contains corresponding labels for the movie_descriptions.csv data
