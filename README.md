# Twitter-Bot-Detection
A decision tree implementation of bot detection for twitter, without using sklearn

The given notebook contains the code to my primitive bot-detection project for Twitter. 
The dataset is first checked for missing values, imbalance is identified and feature extraction is performed.

Then, with the help of NLTK and stopwords, textual data from Tweets is processed.
A bag of words containing most frequent words tweeted by bot accounts is formed.

This is used to compare user data and predicted data of tweet content.

Finally, a decision tree is built based on information gain, which tells us that the friends vs followers count ratio becomes the most informative feature in detecting bot accounts

