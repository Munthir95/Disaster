1. Project Overview 

This project's goal is to make a model and platform to judge what type of information is contained in short messages sent from people in the middle when a disaster occure.

2. Project Component

2.1. app:

run.py to run the app file

2.2. data:

disaster_messages.csv & disaster_categories.csv contain the source files for messages and categories

2.3. model:

train_classifier.py to train and print an evaluation of the model

classifier.pkl contain the saved model from train_classifier.py

3. Installation 

The code should run with no issues using Python versions 3*

Run the following commands in the project's root directory to set up your database and model

To run ETL pipeline that cleans data and stores in database python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db 
To run ML pipeline that trains classifier and saves python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl 
Run the following command in the app's directory to run your web app. python run.py

Go to http://0.0.0.0:3001/

4. Project Motivation
For this project, I was interestested creating a machine learning pipeline to categorize real messages send during disaster events.
