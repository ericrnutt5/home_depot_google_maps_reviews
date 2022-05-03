# home_depot_google_maps_reviews
Python workflow to get common words and phrases from negative Home Depot store reviews

------------------------------

### Necessary Packages
import pandas as pd
import nltk
from collections import Counter
from nltk.corpus import stopwords
from nltk.collocations import *

.csv files obtained from Outscraper tool, but can be done entirely in python if necessary. The Outscraper tool was used for the sake of saving time. See the link below.
https://app.outscraper.com/googleReviews
For the purpose of this project, I pulled max 500 reviews with a rating of 2 stars or less.

------------------------------

# Define a function for generating cleanesed data frame from google maps review .csv
Function applied to the Zillow Group.

------------------------------

# Define function for generating common words list.
This function will generate a list of the most common words (ommiting stopwords) with a word count. 
Apply this function to the dataframe for the Zillow Group.

------------------------------

# Summary & Conclusions
The workflow above reads a .csv of google maps store reviews into a dataframe with the columns: date of review, review author, review text, and review rating (stars). A function is then applied to that new dataframe to get the most common words (ommiting stopwords) for a more efficient analysis of the review text.
