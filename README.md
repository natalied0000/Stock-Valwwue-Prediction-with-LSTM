# Stock-Value-Prediction-with-LSTM

This document serves to accompany Python code for "Stock Value Prediction with LSTM" for Machine Learnine module 2201 at Prague City University by Natalie Dvoranova. The code trains a LSTM model to predict stock value in time series and compares the results to a model trained with same data in Linear Regression.

# Configuration instructions

To use this code, it is recommended to use it in Google Colab (https://colab.research.google.com/).

# Installation instructions:
1. Mount the drive with: from google.colab import drive drive.mount('/content/drive')
2. Upload a .csv file (e.g. from yahoo.finance.com )

# Operating instructions: 
You can use ut as is for Close value calculations (that is a closing value of the day) or change it to other values, e.g. High, Low,... You can change the training/testing proportions to calculate if certain events had specific impact on the stick value (this will result in a new model being trained).

# This project contains:
prototype.ipynb README.md

# Copyright and licensing information:
If you'll use this code, please add a reference to this code in whichever standard you are using.

# Contact information for the distributor or author:
natalie.dvoranova@praguecollege.com

# List of known bugs:
Dates did not convert properly when plotted in LSTM Model vs Linear Regression graph.
