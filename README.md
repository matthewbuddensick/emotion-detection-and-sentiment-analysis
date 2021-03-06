# emotion-detection-and-sentiment-analysis
The data for this project is taken from two different sources:  
  - [Kaggle](https://www.kaggle.com/datasets/praveengovi/emotions-dataset-for-nlp): dataset for modeling emotions  
  - The second dataset I scraped from twitter. It has 5000 tweets mentioning congress, and the tweets are not retweets or quote tweets. The file for this data is called     ScrapeTwitterData.ipynb and the csv file is called tweets_including_congress.csv. 


The model built from the kaggle data will be used to model emotions on the twitter data, and I will also apply sentiment analysis using the Textblob library.   The purpose of this project is to take a look at how people are feeling about congress. Recently there have been a lot of controversial decisions made by parts of the United States government, and there have also been many senseless tragedies. Because of this, I am expecting to uncover many tweets expressing emotions like anger or sadness. I will be testing a range of models either using the default parameters or using GridSearchCV to explore using different parameters to determine the best model to predict emotions from text. At the end I will visualize some of the insights gathered and look at how people are really feeling about the government. 
