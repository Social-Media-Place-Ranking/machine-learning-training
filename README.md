# Machine Learning Training

## Introduction

The code in this repository aims to prepare the data, explore and engineer it, and create a machine learning model to predict its labels for future inputs. 
There's 2 Jupyter Notebooks in this repository: 
- **Data Preperation** : "data_preperation.ipynb"
- **EDA, Feature Engineering and Machine Learning Models** : "EDA, Feature Engineering and ML.ipynb"

## Data Preperation :
This code does the following:
- Read a group of JSON files that have data about real places in New York city
- Map those locations with location-related tweets from a MongoDB cluster that has collected tweets from a certain time frame in New York. [Check this repository](https://github.com/Social-Media-Place-Ranking/Twitter-scraping)
- Extract the following features : ['query', 'document', 'query_length', 'document_length', 'jaccard_entire', 'sub_jaccard', 'prefix_match', 'elasticsearch_score', 'distance']
- Save the resulting dataframe

## EDA, Feature Engineering and Machine Learning Models :
This code does the following:
- Generate Labels for the data that resulted from the Data Preperation
- Exploratory Data Analysis(EDA)
- Feature Engineering
- Build different machine learning models 
- Hyperparameteres Tuning to find the best parameteres 
- Model Interpretation
