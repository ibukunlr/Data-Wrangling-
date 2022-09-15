The dataset used for this report is the tweet archive of the Twitter user @dog_rates known as WeRateDogs.WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. Three datasets were used for this report . We were to gather, access and clean the dataset and derive some insights using python and its' libraries.

The first one was the provided twitter_archived_enhanced csv file, this datset originally contains 17 columns(such as the tweet_id, the names of dogs, the source of the tweet and the text as written by the user etc) which was manually downloaded.

The second dataset was a tsv, named as image_predictions file, this file contains predictions,images_url about the dogs. This was downloaded with the request library and also read into a csv file.

The 3rd dataset was to be gotten directly from twitter but I chose to use the already provided json file.

After gathering the datsets, I accessed them using the various python functions (.info(), .head(), .tail()) to ascertain the type of datasets I'm working with and to check for missing information.. I also applied some python methods (isnull, duplicates()) to check for null values and duplicated values.

From the accessment I did, I arrived at 9 quality issues and 2 tidiness issues , as shown below :

Quality Issues :

Missing values in some columns((in_reply_to_status_id, in_reply_to_user_id,retweeted_status_user_idretweeted_status_id,retweeted_status_timestamp) in df1
2.The timestamp column has the wrong data type

3.The stages of dogs are in lower case

4.Some of the names are written in lower cases

5.Some names of dogs are incorrect.

6.Columns name in df2 aside tweet_id are not descriptive enough

7.Tweet_id datatype is int64 instead of string

8.Inconsistency in the letters of the P1 column, some of them are uppercase, lowercase.

Optimize the source column to make it more readable
Tidiness issues :

1) The columns (doggo,floofer,,pupper and puppo ) are stages of dogs and should be merge together in a column. 2.Df1 and df3 should be merged.

I made the necessary changes i.e cleaning my data by using the Define-Test-Code approach.

After cleaning, I stored the dataset into a master dataframe and made my insights.

