# __Gavin Sentak Portfolio__

## NLP Prediction of Weather Events
Utilizing data sourced from Twitter tweets that were gathered during natural weather events, this project utilizes the text features of each entry to build a model that can classify what kind of event the tweet is related to (Earthquake, Fire, etc.). In order to do this, Google's BERT model is utilized to gather vector representations of each entries text information and then these representations are modeled by different classifiers!

This notebook walks through the steps that are undertaken to turn text data into word embeddings which are then utilized to access the hidden layers of the BERT model. The process that is completed with dummy data is then applied to the actual social media weather data to create final dataframes that are ready to model.
- BERT Transfrom -- [nbviewer](https://nbviewer.jupyter.org/github/gsent12/gsent12.github.io/blob/master/NLP_BERT_Tweet_Weather_Prediction/BERT_Weather_Transform.ipynb)

This notebook takes the model ready data that was created in the prior and runs it through logistic regression and support vector machine classifiers.
- BERT Model -- [nbviewer](https://nbviewer.jupyter.org/github/gsent12/gsent12.github.io/blob/master/NLP_BERT_Tweet_Weather_Prediction/BERT_Weather_Model.ipynb)

## Fantasy Football Visualization Project
Fantasy Football continues to gain popularity within the United States with different people playing their own ways. While some might just choose their favorite players, this notebook attempts to visualize the relevant statistics at each position so that any fantasy team owner could identify value players at relevant position.
- FF Vis -- [nbviewer](https://nbviewer.jupyter.org/github/gsent12/gsent12.github.io/blob/master/Fantasy_Football_Vis_Forecast.ipynb)
