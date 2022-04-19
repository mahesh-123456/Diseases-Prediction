Multiple Disease Predictor
About
This webapp was developed using Flask Web Framework and was deployed on Heroku server. The models used to predict the diseases were trained on large Datasets. All the links for datasets and the python notebooks used for model creation are mentioned below in this readme. The webapp can predict following Diseases:

Diabetes
Breast Cancer
Heart Disease
Kidney Disease
Liver Disease
Malaria
Pneumonia
Models with their Accuracy of Prediction
Disease	Type of Model	Accuracy
Diabetes	Machine Learning Model	98.25%
Breast Cancer	Machine Learning Model	98.25%
Heart Disease	Machine Learning Model	85.25%
Kidney Disease	Machine Learning Model	99%
Liver Disease	Machine Learning Model	78%

NOTE
==> You can access the website live at: https://kvg-disease-predictor.herokuapp.com
==> Python version 3.6.8 was used for the whole project.
==> You can find all the models in models folder.

Steps to run this application in your system
Clone or download the repo.
Open command prompt in the downloaded folder.
Create a virtual environment
mkvirtualenv environment_name
Install all the dependencies:
pip install -r requirements.txt
Run the application
python app.py
Dataset Links
All the datasets were used from kaggle.

Diabetes Dataset
Breast Cancer Dataset
Heart Disease Dataset
Kidney Disease Dataset
Liver Disease Dataset

Links for Python Notebooks used for model creation
Diabetes Notebook
Breast Cancer Notebook
Heart Disease Notebook
Kidney Disease Notebook
Liver Disease Notebook
