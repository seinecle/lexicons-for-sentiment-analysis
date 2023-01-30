# Purpose
This repository lists all publicly available lexicons for sentiment analysis.

It is made available in the hope that it will foster cumulative progress in the domain of lexicon-based sentiment analysis.


# Formatting
The lexicons have been modified to follow the same format:

  term	valence	score	other attributes.

The file is tab-separated (.tsv)

- 1st field: the term. It can be a unigram, bigram or ngram, a out-of-dictionary word, or a non word (emoji, abbreviation...)

- 2nd field: the valence can be "positive" or "negative". When "neutral" terms were found in lexicons, they were removed.
- 3nd field: the score. It can be absent. If present, it has been normalized from -1 (very negative) to +1 (very positive)
- Other fields: attributes can be added as extra columns.

# License
Each lexicon can be associated with a different license. Please check the relevant license in the README file of each folder.


# Citing this repository
Levallois, Clement (2023). "umigon-lexicon: a contribution to inherently interpretable sentiment 
analysis". *In submission*

