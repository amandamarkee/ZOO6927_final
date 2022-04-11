# ZOO6927_final Biology in Pop-Culture: Using Machine Learning to Identify Fictional Species from Pokemon
For the ZOO6927 AI in Biology course, I chose to create a machine learning model that identifies Pokemon based on biological and battle statistics, and a decision tree model for classifying Pokemon into one of 18 types. I use data from Alberto Barradas's Pokemon.csv "Pokemon with stats" dataset. This data set includes 721 Pokemon, including their number, name, first and second type, and basic stats: HP, Attack, Defense, Special Attack, Special Defense, and Speed. Found here ( https://www.kaggle.com/datasets/abcsds/pokemon )

## Project Overview and Criteria
> Select some data that can be analyzed with AI and work to make a notebook that walks through the process of analyzing the data.
> 
> Introduction: Describes the data and where you got the data. Describe the question being answered and the method(s) being used to answer the question.
>
> Data pre-processing: What's needed to load the data, clean the data, normalize, etc.
>
> Model setup: Setup one or more models
>
> Hyperparameter tuning: Do some playing with the model hyperparameters (learning rate, optimizer, batch size, epochs, whatever makes sense)
> 
> Results: How did the model do
> 
> Discussion: Summarize what worked, what didn't etc.


## Linear Regression Model
For my first question, I want to know whether or not I can train a model that will predict a Pokemon "species" name, given battle and biological information. In this dataset, my response variable will be the Pokemon species name, or the column "Name". My predictor variables will be all columns in the lm_dataset, with the "Name" column dropped.


## Decision Tree Classifier Model
For my second question, I want to know whether or not I can train a model that will classify a Pokemon in one of 18 types. In this dataset, my response variable will be the Pokemon's main type, or the column "Type.1". My predictor variables will be all columns in the dt_dataset, with the "Type.1" column dropped.
