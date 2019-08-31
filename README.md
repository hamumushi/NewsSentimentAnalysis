# NewsSentimentAnalysis (ETSA: Economic Text Sentiment Analyzer)

This notebook is based on [LSTM-Sentiment-Analysis](https://github.com/adeshpande3/LSTM-Sentiment-Analysis).
Our paper "Enhanced news sentiment analysis using deep learning methods" is pubulished in [Journal of Computational Social Science](https://link.springer.com/article/10.1007/s42001-019-00035-x)

We obtain the model by Training.ipynb.
In this code, we can choose two word vectors to obtain the model. One is [GloVe](http://nlp.stanford.edu/projects/glove/), and the other is made from Thomson Reuters News Archive from 2003 to 2016 (8856M words).

We apply a pre-trained network to some documents by using Test.ipynb.
In this pre-tarined network, we used word vectors downloaded from [GloVe](http://nlp.stanford.edu/projects/glove/) and training data made from Thomson Reuters News Archive from 2003 to 2012.
