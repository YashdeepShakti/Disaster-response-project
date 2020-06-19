# Disaster-response-project
A machine learning project for Disaster response

In this project, I'll apply data engineering to analyze disaster data from Figure Eight to build a model for an API that classifies disaster messages.

Data directory contains a data set which are real messages that were sent during disaster events. I will be creating a machine learning pipeline to categorize these events so that appropriate disaster relief agency can be reached out for help.

This project will include a web app where an emergency worker can input a new message and get classification results in several categories. The web app will also display visualizations of the data.

#Description 


The project consists of the following parts:

The ETL pipeline in the /data directory, which:

1.Combines the two given datasets (In CSV format)

2.Cleans the data

3.Stores it in a SQLite database


The NLP and Machine Learning pipeline in the '/models' directory, which:

1.Splits the dataset into training and test sets

2.Builds a text processing and machine learning pipeline

3.Trains and tunes a model using GridSearchCV

4.Outputs results on the test set

5.Exports the final model as a pickle file



Usage:

From the /app directory Run the following command to run the web app:
 python run.py   

