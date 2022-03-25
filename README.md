# NLP project: IMDB Sentiment Prediction

## Talbe of Contents
* [Background](#Background)
* [Result](#Result)
* [Conclusion](#Conclusion)
* [Usage](#Usage)

## Background
In this exercise, several classifier models, such as SVM, decision tree, and logistic regression, are applied to predict sentiment of reviews.<br/>IMDB dataset having 50K movie reviews for natural language processing or Text analytics. We use a set of 25,000 highly polar movie reviews for training and 25,000 for testing.
* Click [here](https://ai.stanford.edu/~amaas/data/sentiment/) for more dataset information.
* You also can be accessed [here](https://nbviewer.org/github/huihuang751/NLP_project-IMDB_Sentiment_Prediction/blob/main/IMDB_Sentiment_Prediction.ipynb#Part-4:-Optimization) to see my Jupyter Notbook in detail.

## Result

![](/images/Score.png)

## Conclusion
* Logistic Regression successfully achieve 82% F1 score. 
* Adjusting models' paramters by GridSearchCV, F1 score does not have significant improvement (opt).
* Further clean text by using stop word method keeps F1 score (Cln).
* We suspect it is resulted from bag-of-words method (One-hot encoding).
* One-hot encoding would cause curse of dimensionality and sparse vectors.

## Usage
This project is best viewed in a notebook viewer, which can be accessed [here](https://nbviewer.org/github/huihuang751/NLP_project-IMDB_Sentiment_Prediction/blob/main/IDMB_sentiment_prediction.ipynb). In this notebook, you will find a walk through of the work done and the respective code.
