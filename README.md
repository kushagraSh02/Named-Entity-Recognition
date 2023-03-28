# Named-Entity-Recognition
Performing Named-Entity-Recognition on data using NLP.


The dataset with 1M x 4 dimensions contains columns = ['# Sentence', 'Word', 'POS', 'Tag'] and is grouped by #Sentence.

Columns
Word:
This column contains English dictionary words form the sentence it is taken from.

POS:
Parts of speech tag

Tag:
Standard named entity recognition tags as follows
[
ORGANIZATION - Georgia-Pacific Corp., WHO
PERSON - Eddy Bonte, President Obama
LOCATION - Murray River, Mount Everest
DATE - June, 2008-06-29
TIME - two fifty a m, 1:30 p.m.
MONEY - 175 million Canadian Dollars, GBP 10.40
PERCENT - twenty pct, 18.75 %
FACILITY - Washington Monument, Stonehenge
GPE - South East Asia, Midlothian
]

We perform named entity recognition on data and get an accuract of about 98%.

Dataset URL: https://www.kaggle.com/datasets/namanj27/ner-dataset
