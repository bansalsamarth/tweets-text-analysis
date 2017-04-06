# tweets-text-analysis

tweets.csv is a collection of 20lakh+ tweets. 

Columns in that dataset: twitter_handle, category, tweet_id, create_date, tweet_text

Apart from category, which I added while cleaning the data, rest were obtained from Twitter API. 

analysis.py reads data from tweets.csv file, processes/cleans the tweet_text (eg removes stop words), and then finds most common words, bigrams and hashtags. 