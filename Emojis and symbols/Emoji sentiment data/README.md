# Emoji sentiment data

⚠️ A rule has been applied to the original dataset

The sentiment score of the emojis is the sum of the score for positive valence plus the score for negative valence. Emojis are also scored for their neutral valence. The sum of the three scores equals to one.

By construction, terms that are quasi-neutral can have a sentiment score which is close to but different from zero, which would flag them as "positive" or "negative". We chose to re-clasiffy these terms as "neutral" with the following heuristics:
  
for each term:
	if the score for "neutral valence" is > 0.3 and neither the score for positive valence nor the score for negative valence is above 0.4
		then the valence is annotated as "neutral"
		else, the valence is the sentiment score as indicated in the file.

The folder contains an Excel file showing how this calculation is conducted in practice. It is also possible to retrieve the original values of Novak et al. in this Excel file if necessary.

# License
CC BY 4.0

# Reference
Novak, P. K., Smailović, J., Sluban, B., & Mozetič, I. (2015). Sentiment of Emojis. PLOS ONE, 10(12), e0144296. https://doi.org/10.1371/journal.pone.0144296



# Relevant links

+ https://figshare.com/articles/dataset/Emoji_Sentiment_Ranking/1600931

