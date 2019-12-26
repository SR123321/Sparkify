# Sparkify
Capstone project - Sparkify

Table of Contents
Installation
Project Motivation
Files Description
Result

Installation:
This project uses the following software and Python libraries: Python, Spark, Pyspark, pandas, Matplotlib, Seaborn.
You will also need to have software installed to run and execute a Jupyter Notebook.
If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more included.

Project Motivation:
Sparkify is a fictional music streaming platform created by Udacity. For this project we are given log data of this platform in order to drive insights and create a machine learning pipeline to predict churn.The dataset (128 MB) we use here is a subset of the whole data. We use the power of spark to perform data manipulations and build our models for this problem.

File description:
Sparkify.ipynb  is the main file of the project, it demonstrates the process of using pyspark to explore the data and build the model.

Result:
Based on the model, We can see that UpPerSong (thumbs up/no of songs) is the most important feature in predicting user churn. Other important features include Days (length of the sessions), and DownPerSong (thumbs down/no of songs) for a user.

Licensing, Authors, and Acknowledgements
Must give credit to Udacity for the project. Feel free to use the code here as you would like!

