# Purpose
This repository lists all publicly available lexicons for sentiment analysis.

It is made available in the hope that it will foster cumulative progress in the domain of lexicon-based sentiment analysis.


# Formatting
The files are tab-separated (.tsv)

The lexicons have been modified to follow the same format:

> term	valence	other fields


- 1st field: the term. It can be a unigram, bigram or ngram, a out-of-dictionary word, or a non word (emoji, abbreviation...)
- 2nd field: the valence can be "positive" or "negative". When "neutral" terms were found in lexicons, they were removed.
- other fields are optional. The "score" field is the most common of the optional fields. If present, it has been normalized from -1 (very negative) to +1 (very positive)

# License
Each lexicon can be associated with a different license. Please check the relevant license in the README file of each folder.


# Citing this repository
Levallois, Clement (2023). "umigon-lexicon: a contribution to inherently interpretable sentiment 
analysis". *In submission*

