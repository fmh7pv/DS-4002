# Hypothesis
Using the text data as indicators of rating, predict when books get a rating of above a 4 or above a 5.

# Research Question:
Can we use text data to predict how a user will rate a book on a numeric scale?

## SRC Section:

### Installing/Building the Code:
To run book_spoilers.ipynb, the following packages must be installed: gzip, json, re, os, and csv.

To run the .rmd file, he following packages must be installed and loaded: tm, SnowballC, wordcloudk, RColorBrewer, syuzhet, ggplot2, readr, tidyverse, mice, forcats, tidytext, and tm.

### Usage of Code
In order to start using the data, we needed to convert the JSON file into a .csv file. The file book_spoilers.ipynb contains the code used to execute this conversion. We started by reading in the JSON file line by line and using the json.loads() method to convert the JSON file into a python dictionary. After doing so we were able to use csv.DictWriter() to convert the python dictionary into a csv file ready for use.

The Project1DS4002.Rmd file is used to read in book_spoilers.csv and perform analysis to predict based on textual reviews whether a book will be rated above 4/5 stars. 


## Data Section:

### Link to Data
[Link for book_spoilers.csv](https://drive.google.com/uc?id=196W2kDoZXRPjzbTjM6uvTidn6aTpsFnS)

### Data Dictionary
| Variable | Definition | 
| ------- | --- |
| bookID | A unique number used to identify each book.| 
| average_rating | The average rating (out of five stars) for the given book. |
| rating | The numerical rating, out of five stars, a reviewer gave a given book. | 
| has_spoiler| Indicates whether a book has a spoiler or not. |
| rating | The rating from each reviewer. |


### Notes about use of Data
Average rating was computed by us based on the data given. 

## References Section:

### References
Kolamanvitha, “Twitter sentiment analysis using Logistic Regression”, Nerd for Tech

Mengting Wan, Julian McAuley, "Item Recommendation on Monotonic Behavior Chains", in RecSys'18. [bibtex]

Mengting Wan, Rishabh Misra, Ndapa Nakashole, Julian McAuley, "Fine-Grained Spoiler Detection from Large-Scale Review Corpora", in ACL'19. [bibtex]

S. Mhatre, J. Sampaio, D. Torres, and K. Abhishek, “Text mining and sentiment analysis: Analysis with R,” Simple Talk, 15-Sep-2021. [Online]. Available: https://www.red-gate.com/simple-talk/databases/sql-server/bi-sql-server/text-mining-and-sentiment-analysis-with-r/. 

“UCSD book graph,” UCSD Book Graph. [Online]. Available: https://sites.google.com/eng.ucsd.edu/ucsdbookgraph/home#h.p_VCP_qovwtnn1. 

### Acknowledgements

### Links to M1 and M2 assignments
[M1 assignment](https://docs.google.com/document/d/1IInxMDY9oO2tESe-RPept87km-qJ4UMMXPpHO6I1e3A/edit)

[M2 assignment](https://docs.google.com/document/d/150iemEBRcMvND9n4l-rOIKVf7n7Pg5Nl9x-3jn2PRJY/edit)


