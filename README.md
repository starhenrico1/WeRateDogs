# WeRateDogs
The dataset is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with  commentsabout the dog.


# The aim of this project is to wrangle dataset called WeRateDogs Twitter data by creating a meanful insight.
# PROJECT DETAILS
The preject is sub-divided into four major phase:
* Gathering data
* Accessing Data
* Cleaning data
* Analysis and visualization

# Gathering data
The projects involve three dataset and the dataset has different ways of acquiring the data. The first dataset called twitter-archive-enhanced.csv was provided for anlysis by Udacity. To get access to the data ,i had to directly read the dataset from udacity.

The second dataset was downloaded programmtically by using the request library. A Url " https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv' was provided by udacity. The dataset contaings image predication of the dogs.

The third dataset is to be gathered through twitter API. the first task is to ask by emailing twitter to request for API from twitter .After the API has be provided ,i then query twitter by saving the file as a tweet_json.text.

# Accessing Data
By using both

Visual assessment
Programmatic assessment
Visual assessment: By assessing the data based on what i noticed by just looking at the dataset.

Programmatic assessment: By using pandas functions to assess the dataset

# Quality issues
Timestamp should be in date datatype not object

for archive the source column ,drop irrelevant text to just the source

Remove all row for which columns related to retweets are not null.

Dropping columns not needed for analysis

tweet_id should be in strings

There are 109 non-capitalized words which forms an invalid name

the minimum for both numerator and denominator is 0 (it should be "10") and and the maximum for both is very huge.

Column headers for image_prediction dataframe are not discriptive

# Tidiness Issues:
archieve, image_predictions and tweet_counts should be merged

doggo,floofer,pupper,puppo could be melted into 1 column instead of 4

# Cleaning
this phase is sub_divided into

Define
Code
Test

Define : I define the quality issue ot tideness issue i want to address Code : i describe and write the code i want to use in cleaning this issues. Test : I test the code that i have writing and check the functionality.

# Storing
Storing the clean data as ('twitter_archive_master.csv')

# Analysis and visualization
After cleaning and storing the data i look for insights and visualize
