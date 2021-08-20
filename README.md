# Apple on Twitter

Diego Duque


## Abstract

The purpose of this project is to understand and analyze tweets related to Apple. This company has been getting more and more popular over the years. It is a contemporary reference for high-tech. Using Python brings us the opportunity to massively understanding tweets related to anything, in this case, related to Apple.

## Design
The project is designed to unsupervised learning as a final result. Topic model is also performed and at the end of the code  will be provided sentiment analysis related to the dataset.

## Data
This public [Kaggle](https://www.kaggle.com/seriousran/appletwittersentimenttexts) dataset will be used: 1624 unique values (tweets).

## Methodology 

<img src="https://github.com/dieguque/project5/blob/42fb1ae75639e58bea4b34da990ed49fc9bf4904/charts/Methodology.png">

## Tools

1. Sklearn  
- from sklearn.feature_extraction.text import TfidfVectorizer, ENGLISH_STOP_WORDS  
- from sklearn.decomposition import NMF
- from sklearn.cluster import KMeans
- from sklearn.manifold import TSNE

2. NLTK 
- from vaderSentiment.vaderSentiment import SentimentIntensityAnalyzer

3. Numpy

4. Pandas
- import pandas_datareader.data as web

5. Plotting
- import matplotlib.pyplot as plt
%matplotlib inline
- from mpl_toolkits.mplot3d import Axes3D


## Summary 

### Topic Modeling Conclusions (n = 9):

topic_0: STOCK - AAPL stock price, investing ideas and techinques
topic_1: Negative_Sentiment - f*** and hate
topic_2: Products: Apple products and technical issues
topic_3: Apple_Event - rumors, on new devices, new iPhone
topic_4: Chargers - related to iPhone and macbook charger bad quality
topic_5: STOCK and trade - AAPL stock, and Apple's global trade
topic_6: Positive_Sentiment - happy customers
topic_7: Founders - Steve Jobs and Wozniak
topic_8: Quality - negative coments again broken products and iOS

### Sentiment Analysis:

Positive

<img src="https://github.com/dieguque/project5/blob/ea19d5539083d0376b8f807032dc395935b975f0/charts/positive.png">

Negative

<img src="https://github.com/dieguque/project5/blob/ea19d5539083d0376b8f807032dc395935b975f0/charts/negative.png">

### Kmeans Clustering & plot by using TSNE

k = 9 so here shows 9 different clusters by colors as plotting by this dimensionality reduction method called TSNE on 2 dimensions.
<img src="https://github.com/dieguque/project5/blob/ea19d5539083d0376b8f807032dc395935b975f0/charts/TSNE.png">
