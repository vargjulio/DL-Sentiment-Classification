## Sentiment prediction in movie reviews relying on word2vect and LSTM.

In this task word2vec is used in combination with LSTM to predict sentiment polarity
(positive vs negative) in movie reviews. A word2vec embedding layer is used to obtain 
continuous representations of words while  a Recurrent Neural Network (Long Short-Term Memory) 
allows performing classification/prediction of review polarity. The model explored is compared 
with a baseline comprising a Multinomial Naive Bayes classifier. The prediction accuracy obtained with 
the baseline was 85.7% while the accuracy of the explored model was 87.87%. Future work will include
hyperparameter fine-tuning.
