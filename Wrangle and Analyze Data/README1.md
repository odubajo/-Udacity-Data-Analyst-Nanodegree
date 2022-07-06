
## P3: Analyze Twitter Data

### Prerequisites

Additional installations: 

* [Tweepy](http://www.tweepy.org/)
* [Requests](http://docs.python-requests.org/en/master/)

## Project Overview

### Data Sources

**Name: WeRateDogs™ Twitter Archive (twitter-archive-enhanced.csv)**

- Source: Udacity
- Method of gathering: Manual download

**Name: Tweet image predictions (image_predictions.tsv)**

- Source: Udacity
- Method of gathering: Programmatical download via Requests

**Name: Additional Twitter data (tweet_json.txt)**

- Source: WeRateDogs™
- Method of gathering: API via Tweepy

### Wrangling

**Cleaning steps:**

- Merge the tables together
- Drop the replies, retweets and the corresponding columns and also drop the tweets without an image
- Clean the datatypes of the columns
- Split the text range into two separate columns
- Remove the "None" out of the doggo, floofer, pupper and puppo column and merge them into one column
- Remove the wrong names of name column
- Clean the new breed column by replacing the "_" with a whitespace and make them all lowercase

### Summary

**Questions:**

> what month of the year had the most had the most tweets?
- december of 2015 generated the most tweets, the number of tweets generated declined as the year went on
> what dog breed has the most activity?
- the golden retriever is the dog with the most activity
> is there a relationship between retweets and favorites?
- there is a very high positive correlation between them
### Authors

* Odubajo Abdul Qoyyum
* Udacity


