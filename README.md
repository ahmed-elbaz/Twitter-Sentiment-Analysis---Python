# Twitter-Sentiment-Analysis---Python
## Introduction

The objective of this Kaggle in-class competition is to build a model that will determine the polarity (neutral, positive, negative) of tweets. To do this we will train the model on the provided data. The resulting model will have to determine the class (neutral, positive, negative) of new data (test data that were not used to build the model) with maximum accuracy and fscore.

## Overall Conclusion

Using Bagging + logisiticRegression + countVectorizer + w2v resulted in highest fscore of 66.59% when submitting on kaggle. However, we got perfect fscore, accuracy values when we added additional training data(76% for both) but with some weakness on  fscore values of neutral class which seems to be heavily presented in test data and that’s the reason we didn’t get higher fscore values when we added additional data as training.

## Repository contents

The repository includes

1. twitter-2013train.txt, twitter-2014train.txt and twitter-2015train.txt are the files used for training.
2. test.xlsx file is the test dataset.
3. Twitter Sentiment Aalysis word report that summarizes the effort done in this competition.
4. baseline experiment notebook includes the trials to decide which classifier and vectorizer will be the best for our data.
5. enhancement experiment notebook shows the trials to fine tune our model to achieive the best results.
6. enhancement experiment with additional data notebook shows the results when we tried to add some additional tweets to enhance model
   perfromance.
7. Best model notebook includes the model that worked the best in this competition and achieved the highest f1score in kaggle.

