# Wrangle and Analyze Data: WeRateDogs Tweet Analysis
The project served to analyze tweet data from the WeRateDogs (@dog_rates) Twitter account to determine which tweets were most popular, in terms of retweet and favourite counts.

## DATA GATHERING
There were three different sources for the data required, each source providing a different segment of the data. One source was a CSV file on hand. The second source was a TSV file that I downloaded programmatically. The third source was the Twitter API, which I queried via the Tweepy library in Python, resulting in a text file holding the JSON data.

## DATA WRANGLING
I assessed the data for quality and tidiness, identified 13 issues, and cleaned the data. I combined the 3 data files into a single file, and then addressed missing values, erroneous data and data types. The final dataset had about 1800 tweets.

## FEATURE SELECTION & ENGINEERING
For data analysis, I selected 3 of the features already present in the data: dog rating, dog breed, and dog stage. I also augmented the data with 2 new features, tweet length and image count.

## ANALYSIS
I formulated 6 research questions based on the data. I used descriptive statistics and data visualizations to answer these questions, including correlation, skewness, bar charts, histograms, scatter plots. and heatmaps.

## FINDINGS
I obtained the following insights:
- Tweets that gave higher ratings to dogs were 200% more popular than those that gave lower ratings.
- Longer tweets were 20% more popular than shorter tweets.
- Tweets with 1 image had the lowest response, whilst those with 4 images were 200% more popular.
- Tweets mentioning the floofer and puppo dog stages were the most popular, receiving over 2 times the response of those that didn't mention dog stages.
- Tweets with images of dogs received 25% more retweets and 39% more favourites than tweets with images of other animals.

## TOOLS & SKILLS
Python: requests, Tweepy, Numpy, Pandas, matplotlib, Seaborn, regular expressions