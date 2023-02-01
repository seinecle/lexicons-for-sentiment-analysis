# Purpose
This repository lists all publicly available lexicons for sentiment analysis.

It is made available in the hope that it will foster cumulative progress in the domain of lexicon-based sentiment analysis.

# To keep in mind

1. each lexicon was designed as one component of a larger application. Some lexicons are domain-specific. Please refer to the paper presenting each lexicon for a complete view (the links to the publications can be found in the  README files of each folder).

2. most (but not all) of the lexicons come with a license restricting their use to non commercial research. The license is mentioned in the README files of each folder.

3. if you use any of these lexicons, please cite the reference coming with it (link in the READMEs of the folders).

# Formatting
All lexicons follow the same format, to make it easy to parse them in one go. They are tab-separated (.tsv) in the following way:

> field 1: term

> field 2: the valence

- 1st field: the term. It can be a unigram, bigram or ngram, an out-of-dictionary word, or a non word (emoji, abbreviation, emoticon, etc.)
- 2nd field: the valence can be "positive" or "negative". When "neutral" terms were found in lexicons, they were removed.
- other fields are optional. The "score" field is the most common of the optional fields. If present, it will be the 3rd field and it has been normalized from -1 (very negative) to +1 (very positive).


# License
Each lexicon is associated with a different license. Please check the relevant license in the README file of each folder.


# Citing this repository
Levallois, Clement (2023). "umigon-lexicon: a contribution to inherently interpretable sentiment 
analysis". *In submission*

