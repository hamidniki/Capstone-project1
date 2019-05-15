# Capstone Project1: Spotify Audio Features
This project aims to find a model that predicts the popularity of a song in the dataset based on the song's audio features. 

### Features and the Target Variable: 

#### Features

acousticness        
danceability        
duration_ms         
energy              
instrumentalness,   
key                
liveness            
loudness            
mode             
speechiness         
tempo             
time_signature      
valence             

#### Target Variable:
Popularity - A number between 0 - 100, which is calculated based on the number of times a song was played

### Approach and Results:
After performing data cleaning/wrangling, visualizations and exploratory analysis, supervised learning algorithms were used to train multivariate models. Since the outcome is numerical, this would be a regresison probelem. The regressors used were LASSO and Gradient Boosting Regression. Gradient Boosting performed better than LASSO by achieving:
- R2 on train data: **0.13**
- R2 on test dataon train data, 0.12 on test data and an MSE 

The following stages were performed and the documentation as well as jupyter notebook pertinent to each stage is in this repository:

- Data Wrangling   
- Data Storytelling  
- Exploratory Data Analysis (EDA)  
- In-Depth Analysis (Multivariate Analysis)   
