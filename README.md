## Yelp_SentimentPrediction
Analyzed Yelp reviews against different sentiment dictionaries, through different models to predict sentiment of reviews

##### 1. Data Exploration
The stars rating has been skewed towards 4 & 5 showing that most of the reviewers have given 4 & 5 stars instead of lower star ratings. Whereas the average star rating has been 3.652 which is used
as threshold to separate negative from positive reviews


An Interesting observation that, reviewers use specific food names (bbq, mexican, burrito, taco etc) when they are leaving positive reviews (4 or 5 stars)

Whereas the negative words associated with low average star rating were (worst, terrible, horrible etc)


##### 2. Data Processing and Cleaning

converting the nominal data to text. We tokenized, lower cased, and filtered the stop words (the, an, a etc). Also we decided to drop the words of character length lower than 3 and greater than 25 to get more sensible words.
