# Wordle
Wordle
Data combined from https://observablehq.com/@rlesser/wordle-twitter-exploration#f6 and from https://www.kaggle.com/datasets/benhamner/wordle-tweets on self-reported success in playing Wordle. 
After filtering out non-English tweets, T1 is the number of tweets saying that the person solved the wordle in 1 try; T2 is for two tries; etc. TX is for failing (so using up all 6 tries without success). Tmean is the mean number of tries to achieve success, with TX counted as 7 tries. 
K2 is the number of wordle successes on a given day on the second try for the data in https://www.kaggle.com/datasets/benhamner/wordle-tweets; K3 is for three tries; etc. Note that there is no K1 nor KX, so all of the Kaggle-collected numbers are for 2 - 6 tries. Kmean is the mean of these numbers for the given day.
Unique is the number of distinct letters (3, 4, or 5).
Prev is the prevalence the word, as found in https://link.springer.com/article/10.3758/s13428-018-1077-9#Fig6 (which is where Robert Lesser got his prevalence data).
Rarity is a measure of how rare the letters in the wordle are, calculated from https://www3.nd.edu/~busiforc/handouts/cryptography/letterfrequencies.html
The data run from December 16 (T1 etc. starting date) through March 19 (K1 ending date) with a lot of overlap between the two data sources, but not complete overlap.
