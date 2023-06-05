# CKDClassifier
Repository for Project 2: Chronic Kidney Classifier model development and deployment to classify the patients whether they are CKD or Not CKD. 
A predictive model can help to classify if the person is a CKD patient or not and based on further investigations can generate a risk score for each patient.
These kind of patients need to go through certain lab tests quite often and this data can be put into some kind of AI model that can continuously learn to classify the patients based on the available data.The predictive approach can help healthcare providers optimize their resources and provide more personalized care to each patient.
Please note that only the classification model has been built, trained and working model deployed for prediction on web with the help of Flask App . On the other hand there is still some work to be completed for Streamlit Web app, still some work is in progress.


# CKDClassifier High Level Architecture

![image](https://github.com/Niloth/CKDClassifier/assets/10112571/e163bc16-ca63-44b7-b8d9-3ad4b4f0cc70)

# Dataset details

![image](https://github.com/Niloth/CKDClassifier/assets/10112571/b6b5f075-15fb-4ec1-b353-4affeade645b)

# Dataset Schema

![image](https://github.com/Niloth/CKDClassifier/assets/10112571/95486d3f-a61a-44a0-abf3-ea60ac88975b)
![image](https://github.com/Niloth/CKDClassifier/assets/10112571/699ea21e-8613-4a37-a50b-91c6380640d5)

# Data Pre-processing Pipeline
![image](https://github.com/Niloth/CKDClassifier/assets/10112571/7e35425b-bd9b-47a5-8581-f021b8bdd960)

# Distribution of Numerical Features

![image](https://github.com/Niloth/CKDClassifier/assets/10112571/441e7d18-4d5b-47b8-9a6a-c5b980f1b9cb)

# Installations to be made :
![image](https://github.com/Niloth/CKDClassifier/assets/10112571/cf18181e-6fdb-4067-a526-bb1e2563f68b)
![image](https://github.com/Niloth/CKDClassifier/assets/10112571/812da523-7ce3-464d-bbc9-32f0b1671829)

•	Windows 10 OS
•	Visual Studio Editor for programming
•	Google Chrome for web browsing
•	Flask Framework for Python based application
•	Python language
-	Packages used for Backend development:
•	from flask import Flask, render_template,request,jsonify,redirect,url_for
•	# from jinja2 import escape
•	import numpy as np
•	import pandas as pd
•	import matplotlib.pyplot as plt
•	import matplotlib.style as style
•	style.use('classic')
•	import seaborn as sns
•	from sklearn.preprocessing import OneHotEncoder
•	from sklearn.model_selection import train_test_split
•	from sklearn.linear_model import LogisticRegression
•	from sklearn.impute import KNNImputer
•	from sklearn.metrics import accuracy_score
•	import warnings
•	# from sklearn.externals import joblib
•	import joblib

-	Packages used for Frontend development:
-	Setting up Streamlit environment for web app using Anaconda Navigator and Conda Prompt
o	import streamlit as st
o	import pandas as pd
o	import numpy as np
o	import seaborn as sns 
o	import matplotlib.pyplot as plt
o	import matplotlib.style as style

•	HTML scripting language
o	For frontend HTML Page scripting
•	JavaScript scripting language
o	For frontend scripting

# Streamlit setup process
Please refer to the Technical documentation as uploaded

