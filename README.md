# Data Analysis Udacity - Project - No-4 Wrangle and Analyze Data
At the beginnig was read carefully instructions given by the Udacity on how to gather data for this data wrangling analysis project.

Firstly, I downloaded the data which is a given CSV file named as twitter-archive-enhanced.csv.

Secodnly, I downloaded image_predictions.tsv file from given url link and read the data from this file.

Thirdly, I had to downloaded data using Twitter API. TO do that I had to ask to create developer account on Twitter web page for the purpose of the project. Next step with developer account was to create project on the web page and then I had the following necessery keys: api_key, api_secret_key, access_token and access_secret to have access to tweets archive.

Finally, I had three different dataframes as followed:

archive_df - "twitter-archive-enhanced.csv" was converted into a dataframe and gives information on basic tweet data, 2.tweets_info_df - contain information like tweet_id, no of retweets and no of favorites etc. downloaded via API.
image_predictions_df - contains information about predictions about the image.
All three datasets were ready for assessing in next part.
