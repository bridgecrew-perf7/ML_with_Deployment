# Project: University Student Admission Prediction
> The goal of this project is to predict the admission of a student in an University.

> Dataset: https://www.kaggle.com/adityadeshpande23/admissionpredictioncsv

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Setup](#setup)
* [Usage](#usage)
* [Project Status](#project-status)
* [Room for Improvement](#room-for-improvement)
* [Contact](#contact)
<!-- * [License](#license) -->


## General Information
The goal of this project is to predict the admission of a student in an University taking into account the following points:
- General test score (GRE).
- Test of English as a Foreign Language score (TOEFL).
- University rating.
- Statement of Purpose (SOP).
- Letter of Recommendation (LOR). 
- Cumulative Grade Point Average (CGPA).

Purpose: Practice the implementation of the Linear Regression Machine Learning Model till deployment (Heroku).

## Technologies Used
- Python 3.7.7
- Flask 1.1.2
- Werkzeug 1.0.1
- Heroku 7.59.1


## Setup
requirements.txt:
- attrs==21.4.0
- certifi==2020.6.20
- click==7.1.2
- Flask==2.0.2
- Flask-Cors==3.0.10
- importlib-metadata==4.8.3
- itsdangerous==2.0.1
- Jinja2==3.0.3
- joblib==1.0.0
- lazypredict==0.2.9
- lightgbm==2.3.1
- MarkupSafe==2.0.1
- more-itertools==8.12.0
- numpy==1.19.1
- packaging==21.3
- pandas==1.0.5
- pluggy==0.13.1
- py==1.11.0
- pyparsing==3.0.6
- pytest==5.4.3
- python-dateutil==2.8.2
- pytz==2021.3
- PyYAML==5.3.1
- scikit-learn==0.23.1
- scipy==1.5.4
- six==1.15.0
- threadpoolctl==3.0.0
- tqdm==4.56.0
- typing_extensions==4.0.1
- wcwidth==0.2.5
- Werkzeug==2.0.2
- xgboost==1.1.1
- zipp==3.6.0

To install the requirements.txt file in your environment:
1. cd to the directory where requirements.txt is located.
2. activate your virtualenv.
3. run the command "pip install -r requirements.txt".

To deploy the files into Google Cloud:
1. Create an account on  https://heroku.com/.
2. Create a new project on the console (IAM & admin).
3. Once the project gets created, select Deploy option.
4. Follow the instructions depending on the deployment method used.  


## Project Status
Project is: _complete_ 


## Room for Improvement
The Linear Regression is used for learning purposes but for sure the model can be tested and improved with other Machine Learning Algorithms.

## Contact
Created by [Xavier Nuel Gavaldà](xaviernuelgav@gmail.com) - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
