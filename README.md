<img src="https://github.com/Vaidehii28/Twitter_sentiment_analysis/blob/main/images/bg.jpg">
A Machine Learning Project where we analyze tweets about coronavirus, with the goal of performing a Sentiment Analysis using BERT and roBERTa algorithms to predict the emotion of a tweet.
<br> <br>
<h1>Sentiment Analysis Results:</h1>
The two algorithms performed quite well on the dataset, showing F1 and accuracy scores around 90%.
Such high scores can only be achieved by performing a good cleaning of the original data, allowing the algorithms to learn the most from it.
In particular, also a baseline Naive Bayes Classifier model has been trained to perform the sentiment classification, with a resulting accuracy and F1 around 70% (much lower than BERT).
The training of BERT and roBERTa took around 11 minutes per epoch (for a total of 4 epochs) on GPU per algorithm, since both the transformers parameters (more than 100 million) have been fine tuned to perform the best on the given dataset. It is possible to train only the last layer of the transformer without fine tuning the other parameters: however, this usually leads to inferior results compared to the fine tuning approach.
