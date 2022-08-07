# Wrangle and Analyze Data - We Rate Dogs
## (by Azukaego Uzoagozie Umeononigwe)

## Dataset
The project emphasized on wrangling and analyzing data. The wrangling process involves 3 different stages; gathering, assessment and cleaning. The dataset was gathered from 3 different sources stored at different locations; the twitter_archive_enhanced.csv file which was downloaded manually from the Udacity website, the image_predictions.tsv file which was downloaded programmatically and the tweet_json.txt file provided. The dataset were loaded independently to create three dataframe.


## Summary of Wrangling Process
Initially, the datasets were assessed virtually and programmatically in order to have a better understanding before commencing cleaning. Various quality and tidiness issues were discovered and they were handled individually. Althought the datasets were from three different sources, the cleaned datasets were merged into one final file named 'twitter_archive_master.csv'. The insights were drawn from the cleaned csv file.


## Key Insights
1. A larger percentage of the tweets didn't have identifiable dog stages; 1,651 tweets. 10 tweets were identified as having double stages. Pupper stage had the highest identification with 201 tweets.
2.608 tweets do not have a name identity for the dogs.
3.Rating numerator of 12 has the highest value_counts and the least is rating numerator of zero(0)
4.A positive correlation between retweet_count and favorite_count. As retweet_count increased, favorite_count increased at the same time
