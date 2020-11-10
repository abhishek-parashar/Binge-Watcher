# Binge-Watcher
A Movie Recommendation and review system. Data taken from IMDB. Used collaborative filtering for Recommendation system. Sentiment analysis using NLP. Deployed on Heroku. Developed using Flask.

### Functionalities
- Multilingual, Movies available in almost all the languages.
- Autocomplete Option, Suggests movie names.
<p align='center'>
<img src="https://github.com/abhishek-parashar/Binge-Watcher/blob/main/static/Images/1.jpeg">
</p>

- Details about the cast and information about the cast

<p align='center'>
<img src="https://github.com/abhishek-parashar/Binge-Watcher/blob/main/static/Images/2.jpeg">
</p>
<p align='center'>
<img src="https://github.com/abhishek-parashar/Binge-Watcher/blob/main/static/Images/3.jpeg">
</p>
<p align='center'>
<img src="https://github.com/abhishek-parashar/Binge-Watcher/blob/main/static/Images/4.jpeg">
</p>

- Reviews regarding the particular movie, Classification as positive or negative review

<p align='center'>
<img src="https://github.com/abhishek-parashar/Binge-Watcher/blob/main/static/Images/5.jpeg">
</p>

- Recommended movies, Movies similar to the particular movie.

<p align='center'>
<img src="https://github.com/abhishek-parashar/Binge-Watcher/blob/main/static/Images/6.jpeg">
</p>

### Structure

The directory contains web sub directories and a sub directory for hosting model and other scripts:

1. [main.py](https://github.com/abhishek-parashar/Binge-Watcher/blob/master/main.py)The file which contains all the main backend operations of the website and used to run the flask server locally.
   
2. [Procfile](https://github.com/abhishek-parashar/Binge-Watcher/blob/master/Procfile) for setting up heroku.

3. [requirement.txt](https://github.com/abhishek-parashar/Binge-Watcher/blob/master/requirements.txt) contains all the dependencies.

4. [templates](https://github.com/abhishek-parashar/Binge-Watcher/tree/master/templates) contains the html file.

5. [static](https://github.com/abhishek-parashar/Binge-Watcher/tree/master/static) contains the css file.
  
### Codebase

The entire code has been developed using Python, HTML, CSS, Javascript programming languages and is hosted on Heroku. The analysis and model is developed using SkcitLearn library and various machine learning models, The website is developed using Flask. 

### How to run the project:

  1. Open the `Terminal`.
  2. Clone the repository by entering `https://github.com/abhishek-parashar/Binge-Watcher`.
  3. Ensure that `Python3` and `pip` are installed on the system.
  4. Create a `virtualenv` by executing the following command: `virtualenv venv`.
  5. Activate the `venv` virtual environment by executing the follwing command: `source venv/bin/activate`.
  6. Enter the cloned repository directory and execute `pip install -r requirements.txt`.
  7. Now, execute the following command: `flask run` and it will point to the `localhost` server with the port `5000`.
  8. Enter the `IP Address: http://localhost:5000` on a web browser and use the application.
  
### Dependencies

The following dependencies can be found in [requirements.txt](https://github.com/abhishek-parashar/Reddit-flair-detection/blob/master/requirements.txt):

  1. [scikit-learn](https://scikit-learn.org/)
  2. [Flask](https://palletsprojects.com/p/flask/)
  3. [Gensim](https://radimrehurek.com/gensim/)
  4. [pandas](https://pandas.pydata.org/)
  5. [numpy](http://www.numpy.org/)
  6. [scikit-learn](https://scikit-learn.org/stable/index.html)
  7. [gunicorn](https://gunicorn.org/)
  8. [NLTK](https://www.nltk.org/)
  
### I tried many models for sentiment analysis I got the best results with Multinomial Naive Bayes.
### Recommendation System developed using Cosine similarity (Collaborative Filtering) 

### References
#### 2. For Building machine learning model:
1. https://medium.com/themlblog/splitting-csv-into-train-and-test-data-1407a063dd74
2. https://towardsdatascience.com/multi-class-text-classification-model-comparison-and-selection-5eb066197568
3. https://medium.com/@robert.salgado/multiclass-text-classification-from-start-to-finish-f616a8642538
4. https://www.analyticsvidhya.com/blog/2018/04/a-comprehensive-guide-to-understand-and-implement-text-classification-in-python/
5. https://www.districtdatalabs.com/text-analytics-with-yellowbrick
6. Applied AI course- https://www.appliedaicourse.com/

#### 3.For Building the Website and Deploying it:
1.	https://towardsdatascience.com/designing-a-machine-learning-model-and-deploying-it-using-flask-on-heroku-9558ce6bde7b
2.	https://towardsdatascience.com/deploying-a-deep-learning-model-on-heroku-using-flask-and-python-769431335f66
3.	https://medium.com/analytics-vidhya/deploy-machinelearning-model-with-flask-and-heroku-2721823bb653
4.	https://www.youtube.com/watch?v=UbCWoMf80PY
5.	https://www.youtube.com/watch?v=mrExsjcvF4o
6.	https://blog.cambridgespark.com/deploying-a-machine-learning-model-to-the-web-725688b851c7

