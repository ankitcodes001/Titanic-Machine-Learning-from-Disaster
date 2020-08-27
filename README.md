Titanic: Machine Learning from Disaster
Start here! Predict survival on the Titanic and get familiar with ML basics
The “Titanic: Machine Learning from Disaster” is a classical problem for beginners in Machine Learning.


The challenge is to predict, based on a set of training data, which people would survive the disaster and which would not. Obviously, this is just a challenge to try discover a correlation between the features of the people who survived and not and use it to make predictions.
This is the legendary Titanic ML competition – the best, first challenge for you to dive into ML competitions and familiarize yourself with how the Kaggle platform works.
The competition is simple: use machine learning to create a model that predicts which passengers survived the Titanic shipwreck.
you can download this data set from https://www.kaggle.com/c/titanic/notebooks 



.
It’s a CSV file with 12 columns of information:
The passenger identifier
The label column containing ‘1’ if the passenger survived and ‘0’ if the passenger perished
The class of travel (1–3)
The name of the passenger
The gender of the passenger (‘male’ or ‘female’)
The age of the passenger, or ‘0’ if the age is unknown
The number of siblings and/or spouses aboard
The number of parents and/or children aboard
The ticket number
The fare paid
The cabin number
The port in which the passenger embarked
The second column is the label: 0 means the passenger perished, and 1 means the passenger survived. All other columns are input data from the passenger manifest.
I will build a binary classification machine learning model that reads in all columns, and then makes a prediction for each passenger if he or she survived.


I will the following libray in this project in jupyter notebook'.

numpy

pandas

matplotlib

seaborn

sklearn

