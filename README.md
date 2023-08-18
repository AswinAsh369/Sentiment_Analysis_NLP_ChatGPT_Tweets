# Sentiment_Analysis_NLP_ChatGPT_Tweets

About Dataset

Due to new Twitter API conditions changed by Elon Musk, now it's no longer free to use the Twitter (X) API and the pricing is 100 $/month in the hobby plan. 

This dataset is was updated everyday with the addition of 1000 tweets/day containing any of the words "ChatGPT", "GPT3", or "GPT4", starting from the 3rd of April 2023. Everyday's tweets are uploaded 24-72h later, so the counter on tweets' likes, retweets, messages and impressions gets enough time to be relevant. Tweets are from any language selected randomly from all hours of the day. There are some basic filters applied trying to discard sensitive tweets and spam.

This dataset can be used for many different applications regarding to Data Analysis and Visualization but also NLP Sentiment Analysis techniques and more.

Columns Description:

tweet_id: Integer. unique identifier for each tweet. Older tweets have smaller IDs.

tweet_created: Timestamp. Time of the tweet's creation.

tweet_extracted: Timestamp. The UTC time when the ETL pipeline pulled the tweet and its metadata (likes count, retweets count, etc).

text: String. The raw payload text from the tweet.

lang: String. Short name for the Tweet text's language.

user_id: Integer. Twitter's unique user id.

user_name: String. The author's public name on Twitter.

user_username: String. The author's Twitter account username (@example)

user_location: String. The author's public location.

user_description: String. The author's public profile's bio.

user_created: Timestamp. Timestamp of user's Twitter account creation.

user_followers_count: Integer. The number of followers of the author's account at the moment of the tweet extraction

user_following_count: Integer. The number of followed accounts from the author's account at the moment of the Tweet extraction

user_tweet_count: Integer. The number of Tweets that the author has published at the moment of the Tweet extraction.

user_verified: Boolean. True if the user is verified (blue mark).

source: The device/app used to publish the tweet (Apparently not working, all values are Nan so far).

retweet_count: Integer. Number of retweets to the Tweet at the moment of the Tweet extraction.

like_count: Integer. Number of Likes to the Tweet at the moment of the Tweet extraction.

reply_count: Integer. Number of reply messages to the Tweet.

impression_count: Integer. Number of times the Tweet has been seen at the moment of the Tweet extraction.
