# Twitter-Sentiment-Analysis
Identifying posting on social media using Natural Language Processing

Detecting Hate tweets - twitter sentiment analysis :

Abstract :

Toxic online content has become a major issue in today's world due to increasing use of the internet. Differentiating offensive language and hate speech has become a key challenge.In this report I propose an approach to classify tweets as hate speech or non-hate speech.Using the Twitter dataset , I  use TF IDF to preprocess the data then feed it into multiple ML models.

Overview :

Goal is to classify tweets into 2 categories , hate and non hate speech. The project analyzed 31935 tweets from the kaggle dataset. The first step to  preprocess the data using TF IDF.Before feeding the data into various algorithms data cleaning was done.Data cleaning was done by using lemmatization , removal of stop words , and omissions.Lemmatization removes the inflectional endings of words and returns the base form of itself.A stop word is a commonly used word, such as “the”, “a”, “an”, “in”, that I programmed to ignore . The last step is to omit any foreign characters and Greek symbols.

Results and Conclusion :

Comparative analysis of Logistic Regression, Naive Bayes, Random Forest and SGD  Classifier was performed. The results showed that Logistic Regression performs comparatively better with the TF IDF approach.After training models  the best results achieved were a f1 score of 65 on applying Logistic Regression model. 


Data Source : data

Code link : click here
