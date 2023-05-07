# DS 4002 Case Study: Using text data to predict how a user will rate a book on a numeric scale. 

This case study relies on text data as indicators of rating, the goal is to predict when books get a rating of above or below average

Before you begin working please read the hook and the materials. These will give you guidance as to context/motivation and the deliverable of this assignment. 

## Data Section:
Data can be found in the data folder. Its sourced from this [website](https://drive.google.com/uc?id=196W2kDoZXRPjzbTjM6uvTidn6aTpsFnS)

Here is the [dataset](https://drive.google.com/file/d/1cx1xl5_ctHvgSSTsOH14CaylIg5dVTR4/view?usp=sharing)

We only want 100,000 random reviews. 


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

The goal is to get the dataset to look like this, the data walk through will be assist you in getting to this finalized data set.

| Variable | Definition | 
| ------- | --- |
| text | The cleaned review sentences from each user.  | 
| has_spoiler| Indicates whether a book has a spoiler or not. |
| bookID | A unique number used to identify each book.| 
| above_average | A column indicating whether the books average rating is above 4 or not.  |



## Coding Walkthrough

The walk throughs will assist you in cleaning up the text and analysis of the data. 

[Code Walk through, EDA](https://www.red-gate.com/simple-talk/databases/sql-server/bi-sql-server/text-mining-and-sentiment-analysis-with-r/)

[Sentiment Analysis](https://rpubs.com/Argaadya/529538)
