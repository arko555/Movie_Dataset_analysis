# Movie Revenue Prediction
In this dataset, there are 7398 movies and a variety of metadata obtained from The Movie Database (TMDB). Movies are labeled with id. Data points include cast, crew, plot keywords, budget, posters, release dates, languages, production companies, and countries.
The objective is to analyse the dataset and extract features which provide and insight into what variables decide a success or flop Movie and an attempt to model the same to predict revenue for movies that have just been released 

Link to dataset and further details: https://www.kaggle.com/c/tmdb-box-office-prediction/data?select=train.csv

Edit : Certain Outputs have been cleared since the file size was larger than github's limit. Feel free to try them out on your own

Methodology :
* Transfrom all string and JSON formatted data to extract useful information
* Perform Time-Based Analysis to check impact of Revenue
* Check correlation and causality between independent features and Revenue generation
* Encode extracted string features to understand impact of Genre, Production House, Cast on movie Revenue
* Perform dimensionality reduction to remove redundancy and convert to dense matrix
* Tune and Train multiple models including Ridge_Regression, GradientBoost and XGBoost
* Evaluate Models to analyse their Predictive Power
