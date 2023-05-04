<img src="https://github.com/Vaidehii28/Twitter_sentiment_analysis/blob/main/images/bg.jpg">
A Machine Learning Project where we analyze tweets about coronavirus, with the goal of performing a Sentiment Analysis using BERT and roBERTa algorithms to predict the emotion of a tweet.
<br> <br>
<h1>INTRODUCTION:</h1> 
Twitter has become a crucial platform for individuals to share their opinions and emotions about various topics, including the ongoing coronavirus pandemic. Sentiment analysis is a powerful tool that can be used to extract valuable insights from Twitter data. In this study, we utilized BERT and roBERTa models to perform sentiment analysis on a dataset of coronavirus-related tweets.<br><br>
<img src="https://github.com/Vaidehii28/Twitter_sentiment_analysis/blob/main/images/intro.jpg">
<br><br>
<h1>About roBERTa:</h1>
<br><br>
<img src="https://github.com/Vaidehii28/Twitter_sentiment_analysis/blob/main/images/roberta.jpg">
<br><br>
<h1>DATASET:</h1>
<img src="https://github.com/Vaidehii28/Twitter_sentiment_analysis/blob/main/images/data.jpg">
The dataset used in this study consisted of 48,000 tweets that were collected between March 2020 and May 2021. The tweets were preprocessed by removing stopwords, usernames, and hashtags.
<br>
<h1>Sentiment Analysis Results:</h1>
<br>
<img src="https://github.com/Vaidehii28/Twitter_sentiment_analysis/blob/main/images/result.jpg">
<br><br>
The two algorithms performed quite well on the dataset, showing F1 and accuracy scores around 90%.
Such high scores can only be achieved by performing a good cleaning of the original data, allowing the algorithms to learn the most from it.
In particular, also a baseline Naive Bayes Classifier model has been trained to perform the sentiment classification, with a resulting accuracy and F1 around 70% (much lower than BERT).
The training of BERT and roBERTa took around 11 minutes per epoch (for a total of 4 epochs) on GPU per algorithm, since both the transformers parameters (more than 100 million) have been fine tuned to perform the best on the given dataset. It is possible to train only the last layer of the transformer without fine tuning the other parameters: however, this usually leads to inferior results compared to the fine tuning approach.
<br><br>
<img src="https://github.com/Vaidehii28/Twitter_sentiment_analysis/blob/main/images/thankyou.jpg">
