# Sentiment-Analysis-using-Pre-trained-Glove-Vector-and-Neural-Network
The challenge is to obtain Ten-fold cross validation auc score more than 0.803. After basic cleaning and spelling correction i used pre-trained Glove vector to find 200D representation for words in tweet which are there in Glove Vector words dictionary. Then i summed the (matching) vectors to obtain 200D feacture vector for each tweet. Atlast, i fitted a neural network with 1 hidden layer. I obtained 0.83 10-Fold cross validation auc score.
