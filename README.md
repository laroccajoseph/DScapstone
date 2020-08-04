# Udacity Data Science Capstone Project
  This repo contains the required files to replicate Joseph La Rocca's Data Science Capstone Project, done for Udacity.

# Project Goal: Understanding Small Business Loan Data
  
  1. Installation
  This project was instantiated on a Jupytr Notebook running Python 3.6 in the IBM Cloud. For exact results, please use the same set up. The following libraries are required to run the project:
  -import types
  -import pandas as pd
  -import numpy as np
  -from botocore.client import Config
  -import ibm_boto3
  -import seaborn as sns
  -import matplotlib.pyplot as pl
  -import sklearn as sk
  -from sklearn.metrics import accuracy_score
  -from sklearn.model_selection import train_test_split
  -from sklearn.metrics import fbeta_score
  -from sklearn.ensemble import RandomForestClassifier
  -from time import time
    
  2. Project Motiavtion
  
  The US Small Business administration finds itself helping facilitate loans from banks to small businesses consistently since its inception in 1953. During its life, the loans it has facilitated have been a primary driver of growth for the American jobs market as well as the social benefits small, local business drives for the communities where it flourishes. ‘Flourishes’ here is an operative word, in times of recession, when small business flounders, it results in a destructive domino effect that can ravage local communities. No more haunting is that reality than when we look at the state of catastrophe small businesses are in now due to COVID-19. With this paper, I am hoping to harken back to an earlier time in the US economy, pre-COVID, and analyze the collective powerhouse that is the Small Business, and see if we could use past loan data to predict future business success, and more importantly highlight where future business failures could be. With our current reality, the room for failure grows ever smaller.
  
  Read more on Medium - https://medium.com/@josephdantelarocca/random-forest-classification-on-small-business-loans-ecbd5ec7b415
  
  3. File Record
  
  Capstone Project - Python Notebook where the code is located
  
  4. Acknowledgements
  
  The data utlized in the project was provided by Kaggle, at the following URL - https://www.kaggle.com/mirbektoktogaraev/should-this-loan-be-approved-or-denied/data
  
  Udacity is credited with helping facilate this code in both teaching me how to use Data Scince skills and providing some of the visualization code
