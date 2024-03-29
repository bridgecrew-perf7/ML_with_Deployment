# Diabetes Prediction Project 

## Table of Contents
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Setup](#setup)
* [Deployment](#deployment)
* [Project Status](#project-status)
* [Room for Improvement](#room-for-improvement)
* [Contact](#contact)
<!-- * [License](#license) -->


## General Information
The goal of this project is to predict whether a person is diabetic or not taking into account the following medical parameters:

List of Algorithms:
- Logistic Regression.
- Decision Tree.
- Random Forest.
- XGBoost.
- K-Nearest Neighbors.
- Support Vector Machines.
- Naive Bayes.
- Linear Discriminant Analysis.

Hyperparameter tunning and Ensemble techniques like Passing, Pagging and K-fold Cross Validation are also used.

Dataset: https://www.kaggle.com/adityadeshpande23/admissionpredictioncsv

## Technologies Used
- Python 3.8.5
- Flask 1.1.1
- Werkzeug 0.16.0
- Gheroku/7.56.0 linux-x64 node-v12.21.0


## Setup
requirements.txt:
- certifi==2019.11.28
- chardet==4.0.0
- Click==7.0
- Flask==1.1.1
- Flask-Cors==3.0.8
- greenlet==1.1.0
- gunicorn==20.0.4
- heroku==0.1.4
- idna==2.10
- itsdangerous==1.1.0
- Jinja2==2.10.3
- joblib==0.14.1
- MarkupSafe==1.1.1
- numpy==1.18.0
- pandas==0.25.3
- pep517==0.10.0
- python-dateutil==2.8.1
- pytz==2019.3
- requests==2.25.1
- scikit-learn==0.22
- scipy==1.4.1
- six==1.13.0
- SQLAlchemy==1.4.20
- threadpoolctl==2.1.0
- toml==0.10.2
- urllib3==1.26.6
- Werkzeug==0.16.0
- wincertstore==0.2

To install the requiriments.txt file in your environment:
1. cd to the directory where requirements.txt is located.
2. activate your virtualenv.
3. run the command "pip install -r requirements.txt".

To deploy the files in Heroku follow the deployment rules.

## Deployment
Project deployed on Heroku: https://diabetes-prediciton-2022.herokuapp.com/

![preview img](classificationShot.png)


## Project Status
Project is: _complete_ 


## Room for Improvement
The classification algorithms are used for learning purposes but for sure the model can be tested and improved with other Machine Learning Algorithms.


## Contact
Created by [Xavier Nuel Gavaldà](xaviernuelgav@gmail.com) - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
