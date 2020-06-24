# Text-Classification
Tried to replicate an awesome article which i found on text classification.
I tried using some classification algorithms and tried CNN as was given int the article...



    Classifiers                     Yelp data  Amazon data  IMDB data 

    Logistic(CountVectorizer)        83%         77%         74%    
      Logistic(TF-IDF)               82%         78%         76%    
       XGBoost(CountVectorizer)      77%         71%         69%    
        XGBoost(TF-IDF)              75%         74%         65%    
    RandomForest(CountVectorizer)    80%         76%         74%    
        RandomForest(TF-IDF)         73%         75%         71%


These are the results which I got using the machine learning classification algorithm.

ABOUT DATA
Sentiment Labelled Sentences Data Set from the UCI Machine Learning Repository. This data set includes labeled reviews from IMDb, Amazon, and Yelp, Each review is marked with a score of 0 for a negative sentiment or 1 for a positive sentiment.
