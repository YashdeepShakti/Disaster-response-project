# Disaster-response-project
A machine learning project for Disaster response

In this project, I'll apply data engineering to analyze disaster data from Figure Eight to build a model for an API that classifies disaster messages.

Data directory contains a data set which are real messages that were sent during disaster events. I will be creating a machine learning pipeline to categorize these events so that appropriate disaster relief agency can be reached out for help.

This project will include a web app where an emergency worker can input a new message and get classification results in several categories. The web app will also display visualizations of the data.


#Content



1.Data


process_data.py: reads in the data, cleans and stores it in a SQL database. Basic usage is python process_data.py MESSAGES_DATA CATEGORIES_DATA NAME_FOR_DATABASE
disaster_categories.csv and disaster_messages.csv (dataset)
DisasterResponse.db: created database from transformed and cleaned data.
2.Models


train_classifier.py: includes the code necessary to load data, transform it using natural language processing, run a machine learning model using GridSearchCV and train it. Basic usage is python train_classifier.py DATABASE_DIRECTORY SAVENAME_FOR_MODEL
3.App




run.py: Flask app and the user interface used to predict results and display them.



templates: folder containing the html templates
