# tweets-text-analysis

tweets.csv is a collection of 20lakh+ tweets. 

Columns in that dataset: twitter_handle, category, tweet_id, create_date, tweet_text

Apart from category, which I added while cleaning the data, rest were obtained from Twitter API. 

analysis.py reads data from tweets.csv file, processes/cleans the tweet_text (eg removes stop words), and then finds most common words, bigrams and hashtags. 

GitHub doesn't allow files>100MB. So I uploaded the tweets.csv file (376MB) on Google Drive. Download using this link: https://drive.google.com/open?id=0B_GfKIGtkQk5d3VVaVhMZ0c1R2M