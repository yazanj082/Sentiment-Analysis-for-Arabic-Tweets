# Sentiment-Analysis-for-Arabic-Tweets

Build a Naïve Bayes Classifier that can identify the public opinion of unseen tweets.  You will be given a set of Arabic tweets that are either classified into positive, negative, or neural. 
Take care of:
1.	Word Tokenization: splitting the text into uni-gram tokens. You can also try ‘bi-gram and/or tri-gram tokens

2.	Tokens normalization: Search for a suitable Arabic stemmer and use it to normalize the text.

3.	Conduct adequate text cleaning and preprocessing to eliminate special characters and noisy characteristics. 

4.	Use CountVectorizer and TfidfVectorizer (but not together) for feature extraction.
TfidfVectorizer: has many important parameters that can certainly enhance the performance of the model.

5.	Build the model using MultinomialNB 

6.	Model evaluation: Calculate the precision, recall, F1-score, and AUC of the model.
