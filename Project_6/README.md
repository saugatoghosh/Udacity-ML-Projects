# Udacity Machine-Learning Engineer Nanodegree Capstone Project

## Project Overview

In a world where movies made an estimated $41.7 billion in 2018, the film industry is more popular than ever. It is at the forefront of creating artistic and cultural trends that impact billions of viewers worldwide. Films can bring to us stories that need to be told and help shape public opinion through their unique blend of entertainment and widespread reach. For the industry to continue to thrive and make meaningful contributions to society it is important for it also to be profitable and for films to make money. But what movies make the most money at the box office? How much does a director matter? Or the budget? For some movies, it is "You had me at 'Hello.'" For others, the trailer falls short of expectations and you think "What we have here is a failure to communicate." 
In this Udacity Machine Learning Engineer Nanodegree capstone project, which is based on this Kaggle Competition , we are presented with metadata on over 7,000 past films from The Movie Database to try and predict their overall worldwide box office revenue. 
We are provided with two csv files (train and test) containing names of 7398 movies and a variety of metadata obtained from The Movie Database (TMDB). Movies are labelled with id. Data points include cast, crew, plot keywords, overview, budget, posters, release dates, languages, production companies and countries, the genres each movie belongs to, its popularity and runtime, etc in both datasets. 
The project objective is to predict the worldwide revenues for 4398 movies in the test file. The test data has 22 columns, one less than the train dataset as the revenue information for the test set movies is not given. 
This dataset has been collected from TMDB. The movie details, credits and keywords have been collected from the TMDB Open API as part of the Kaggle competition. The train and test data along with a sample submission file are included in the capstone project github repository.


## Software Requirements

In order to run the project Python 3.5(preferably using Anaconda platform is necessary along with the following packages:

- Python stack: Python 3.5.3 numpy, scipy, sklearn, pandas, matplotlib
- XGBoost
- Light GBM
- CatBoost

