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

### Notes about use of Data

## References Section:

### References

### Acknowledgements

### Links to M1 and M2 assignments



