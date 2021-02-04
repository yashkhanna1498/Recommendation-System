# Binge-and-Popcorn Recommendation-System

Content Based Recommender System recommends movies similar to the movie user likes and analyses the sentiments on the reviews given by the user for that movie.

For Dataset:
The details of the movies(title, genre, runtime, rating, poster, etc) were fetched using an API by TMDB, and using the IMDB id of the movie in the API,web scraping was done to get the reviews given by the user in the IMDB site using beautifulsoup4 and performed sentiment analysis on those reviews. Used Kaggle IMDB 5000 Dataset and The Movies Dataset as well to make a consolidated dataset. 

<p align='center'>
<img src="https://github.com/yashkhanna1498/Recommendation-System/blob/main/images/Screenshot%20(129).png?raw=true">
</p>

<p align='center'>
<img src="https://github.com/yashkhanna1498/Recommendation-System/blob/main/images/Screenshot%20(130).png?raw=true">
</p>

- Details about the movie 
<p align='center'>
<img src="https://github.com/yashkhanna1498/Recommendation-System/blob/main/images/Screenshot%20(131).png?raw=true">
</p>

- Cast
<p align='center'>
<img src="https://github.com/yashkhanna1498/Recommendation-System/blob/main/images/Screenshot%20(132).png?raw=true">
</p>

<p align='center'>
<img src="https://github.com/yashkhanna1498/Recommendation-System/blob/main/images/Screenshot%20(135).png?raw=true">
</p>


- Reviews along with sentiment of the review classified as positive or negative 

<p align='center'>
<img src="https://github.com/yashkhanna1498/Recommendation-System/blob/main/images/Screenshot%20(133).png?raw=true">
</p>

- Recommended movies, similar to the particular movie.

<p align='center'>
<img src="https://github.com/yashkhanna1498/Recommendation-System/blob/main/images/Screenshot%20(134).png?raw=true">
</p>

  
### Dependencies

The following dependencies can be found in requirements.txt file:

  1. [scikit-learn](https://scikit-learn.org/)
  2. [Flask](https://palletsprojects.com/p/flask/)
  3. [pandas](https://pandas.pydata.org/)
  4. [numpy](http://www.numpy.org/)
  5. [scikit-learn](https://scikit-learn.org/stable/index.html)
  6. [NLTK](https://www.nltk.org/)
  
### Recommendation System developed using Cosine similarity and sentiment analysis done using Multinomial naive Bayes. The entire code has been developed using Python, HTML, CSS, Javascript programming languages and is hosted on Heroku. The analysis and model is developed using SkcitLearn library and various machine learning models, The website is developed using Flask. 
Data taken from IMDB. Used collaborative filtering for Recommendation system. Sentiment analysis using NLP. Deployed on Heroku. Developed using Flask. Movies available in English for now. Autocomplete Option, Suggests movie names.

### References
    https://www.youtube.com/watch?v=UbCWoMf80PY
    https://www.youtube.com/watch?v=mrExsjcvF4o
    https://blog.cambridgespark.com/deploying-a-machine-learning-model-to-the-web-725688b851c7
    https://youtu.be/8KO-rdsWMjk

#### Disclaimer: I have referred many sources and this is not my original work.
