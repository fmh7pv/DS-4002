# DS 4002 Case Study: Using text data to predict how a user will rate a book on a numeric scale. 

This case study relies on text data as indicators of rating, predict when books get a rating of above a 4 or above a 5.

## Data Section:
Data can be found in the data folder. Its sourced from this [website](https://drive.google.com/uc?id=196W2kDoZXRPjzbTjM6uvTidn6aTpsFnS)


### Data Dictionary

The orginial data set looks like this 

| Variable | Definition | 
| ------- | --- |
| userID | A unique number used to identify each user. |
| timestamp | Timestamp of the review. |
| review_sentences | Raw review sentences from each user. |
| rating | The numerical rating, out of five stars, a reviewer gave a given book. | 
| has_spoiler| Indicates whether a book has a spoiler or not. |
| bookID | A unique number used to identify each book.| 
| reviewID | A unique number used to identify each review.| 

The goal get the dataset to look like this 

| Variable | Definition | 
| ------- | --- |
| text | The cleaned review sentences from each user.  | 
| has_spoiler| Indicates whether a book has a spoiler or not. |
| bookID | A unique number used to identify each book.| 
| above_average | A column indicating whether the books average rating is above 4 or not.  |



## Coding Walkthrough

[Code Walk through, EDA](https://www.red-gate.com/simple-talk/databases/sql-server/bi-sql-server/text-mining-and-sentiment-analysis-with-r/)

[Sentiment Analysis](https://rpubs.com/Argaadya/529538)
