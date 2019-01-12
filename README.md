# Yelp-sentiment-analysis
Sentiment analysis of yelp data using deep learning. The yelp reviews data can be downloaded from [Here](https://www.yelp.com/dataset).

### The notebook ['preprocess_data.ipynb'](https://nbviewer.jupyter.org/github/vishalbharti1990/Yelp-sentiment-analysis/blob/master/preprocess_data.ipynb) pre-processes the yelp dataset and extracts 100,000 positive, neutral and negative reviews.

### The notebook ['yelp_sentiment_analysis.ipynb'](https://nbviewer.jupyter.org/github/vishalbharti1990/Yelp-sentiment-analysis/blob/master/yelp_sentiment_analysis.ipynb) does two tasks:
1. 70-30 split the 300,000 reviews (proportional wrt classes) into training and test sets and then uses keras to train and test a deep learning model.
2. 70-30 split the 200,000 reviews (positive and negative reviews) into training and test sets (proportional wrt classes) and then uses keras to train and test a deep learning model.
