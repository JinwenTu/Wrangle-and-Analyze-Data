# Wrangle-and-Analyze-Data
Udacity Data Analyst Nanodegree Project 4

Real-world data rarely comes clean. Using Python and its libraries, the dataset I was wrangling, analyzing and visualizing is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.

Key Points to keep in mind when data wrangling for this project:

1. I only wanted original ratings (no retweets) that have images. Though there are 5000+ tweets in the dataset, not all are dog ratings and some are retweets.

2. Assessing and cleaning the entire dataset completely would require a lot of time, and is not necessary to practice and demonstrate your skills in data wrangling. Therefore, the requirements of this project are only to assess and clean at least 8 quality issues and at least 2 tidiness issues in this dataset.

3. Cleaning includes merging individual pieces of data according to the rules of tidy data.

4. The fact that the rating numerators are greater than the denominators does not need to be cleaned. This unique rating system is a big part of the popularity of WeRateDogs.

5. I did not gather the tweets beyond August 1st, 2017 since the image predictions are only provided for the limited time period.

To complete this project, I generated the following files:

1. wrangle_act.ipynb: code for gathering, assessing, cleaning, analyzing, and visualizing data;

2. wrangle_report.pdf or wrangle_report.html: documentation for data wrangling steps: gather, assess, and clean;

3. act_report.pdf or act_report.html: documentation of analysis and insights into final data;

4. twitter_archive_enhanced.csv: file as given;

5. image_predictions.tsv: file downloaded programmatically;

6. tweet_json.txt: file constructed via API;

7. twitter_archive_master.csv: combined and cleaned data.
