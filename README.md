# Detecting SMS Spam Using Natural Language Processing

## Table of Contents
  * [Demo](#demo)
  * [Introduction](#introduction)
  * [Dataset](#dataset)
  * [Technologies Used](#technologies-used)
  * [Accuracy](#accuracy)
  
## Demo 
Link: https://spam-detector-01.herokuapp.com/ <br><br>
[![spam](https://user-images.githubusercontent.com/73738015/103438864-e43ffb80-4c5d-11eb-9ead-8645a320db7f.JPG)](https://spam-detector-01.herokuapp.com/)

## Introduction
This is a Spam Classifier web application built using Flask and deployed on Heroku platform. <br>
The app takes a message/email as an input and predict the message/email as spam or not spam (ham).

## Dataset
I have used the open-source [Spambase dataset](http://archive.ics.uci.edu/ml/datasets/Spambase/) from the UCI machine learning repository. <br>
It contains 5572 rows and 2 columns. Each row represents the message in the text is spam or ham(not spam).


## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/) [<img target="_blank" src="https://number1.co.za/wp-content/uploads/2017/10/gunicorn_logo-300x85.png" width=280>](https://gunicorn.org) [<img target="_blank" src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" width=200>](https://scikit-learn.org/stable/) 

## Accuracy  
Accuracy Score: 98%
