# Sentiment-Analysis-Amazon-Product-Reviews-
Performed sentiment analysis on Amazon Review Dataset available at http://jmcauley.ucsd.edu/data/amazon/

In this project we have consider only the reviews from cloths, shoes and beauty products reviews from the amazon.

Based on these input factors, sentiment analysis is performed on predicting the helpfulness of the reviews and for that we used Long short term memory. Moreover, we also designed item-based collaborative filtering model based on k-Nearest Neighbors to find the 2 most similar items.


# Converted the JSON file to CSV format using: -

dataframe = pd.read_json('reviews.json')
dataframe.to_csv('reviews.csv', sep=',', index=False)
