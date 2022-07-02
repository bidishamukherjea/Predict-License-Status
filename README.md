# Predict-License-Status

The Jupyter Notebook is for the project to Predict the licence status of the data. 

TARGET COLUMN: 'LICENSE STATUS' 

INPUT COLUMN:
'ID', 'LICENSE ID', 'ACCOUNT NUMBER', 'SITE NUMBER', 'LEGAL NAME','DOING BUSINESS AS NAME', 'ADDRESS', 'CITY', 'STATE', 'ZIP CODE','WARD', 'PRECINCT', 'WARD PRECINCT', 'POLICE DISTRICT', 'LICENSE CODE','LICENSE DESCRIPTION', 'LICENSE NUMBER', 'APPLICATION TYPE','APPLICATION CREATED DATE', 'APPLICATION REQUIREMENTS COMPLETE','PAYMENT DATE', 'CONDITIONAL APPROVAL', 'LICENSE TERM START DATE','LICENSE TERM EXPIRATION DATE', 'LICENSE APPROVED FOR ISSUANCE','DATE ISSUED', 'LICENSE STATUS CHANGE DATE', 'SSA', 'LATITUDE','LONGITUDE', 'LOCATION'

We have used Pycaret to find the best model for the dataset. 
Using Pycaret, we found that Gradient Boosting Classifier best suits our needs.
The Prediction is made on the test dataset based on the above model.
