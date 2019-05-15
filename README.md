# Capstone Project1: Spotify Audio Features
This project aims to find a model that predicts the popularity of a song in the dataset based on the song's audio features. The dataset has ~116,000 rows and 17 columns. 

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
- R2 on train data: **0.14**
- R2 on test data: **0.12**
- MSE on test data = **4.2**

### Final Report:
https://github.com/hamidniki/Capstone-project1/blob/master/Hamid-Niki-Capstone-Project1-Final-Report.pdf

### Final Presentation:
https://github.com/hamidniki/Capstone-project1/blob/master/Hamid-Niki-Capstone-Project1-Presentation.pdf

The work on this project was divided into the following 4 phases. To see the documentation pertinent to each phase click on the links provided:

- **Data Wrangling**  
https://github.com/hamidniki/Capstone-project1/blob/master/Capstone%201%20Data%20Wrangling.ipynb
https://github.com/hamidniki/Capstone-project1/blob/master/Hamid%20Niki-Capstone%20Project1%20Data%20Wrangling.pdf

- **Data Storytelling**  
https://github.com/hamidniki/Capstone-project1/blob/master/Capstone-Project1-Data-Storytelling.ipynb
https://github.com/hamidniki/Capstone-project1/blob/master/Hamid-Niki-Capstone-Project1-Data-Storytelling.pdf

- **Exploratory Data Analysis (EDA)**   
https://github.com/hamidniki/Capstone-project1/blob/master/Capstone-Project1-EDA.ipynb
https://github.com/hamidniki/Capstone-project1/blob/master/Hamid-Niki-Capstone-Project1-EDA.pdf

- **In-Depth Analysis (Multivariate Analysis)**   
https://github.com/hamidniki/Capstone-project1/blob/master/Capstone-Project1-In-Depth-Analysis.ipynb
https://github.com/hamidniki/Capstone-project1/blob/master/Hamid-Niki-Capstone-Project1-In-Depth-Analysis.pdf
