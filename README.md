# NLP-Self-Driving-Cars

Overview : In this assignment, you will practice using natural language processing techniques to understand tweets about self-driving cars. You will analyze a set of tweets and find the words in the tweets that are most predictive of positive, neutral or negative sentiments about self- driving cars.

Tasks 

The data file for you to analyze is in the assignment in Canvas. For the purposes of ththe questions below, you can ignore the unit_state, sentiment_gold and sentiment_gold_reason fields, as only a few of the observations have been tagged this way, although you may find it instructive to compare the automatically calculated sentiment to the human-generated sentiment_gold and sentiment_gold_reason field where they are available).
1) Perform exploratory data analysis (for example summary statistics and histograms on the numeric fields) on the data and indicate if you foresee any problems using the data to build a model to predict sentiment. 
2) Tokenize the Tweets for analysis (words, and punctuation, e.g. "!!!", will be relevant). Show the most common words/tokens overall, nouns, adjectives, and punctuation-based tokens for all of the tweets. You should exclude stopwords and the frequent words/phrases like “self- driving cars” that do not help in the prediction task. (Note: if you decide to stem or lemmatize the words for modeling in the following step, which is recommended, you should do that after the part of speech tagging in this step.) 
4) Create a model to predict what sentiment a Tweet will be given on the 1-5 scale. What are the 10 top words/tokens for each sentiment rating? 
5) Evaluate how well the model performs for each rating (1-5). Where does it make errors and how might you improve it? 



Learning to classify text can be found at http://www.nltk.org/book/ch06.html
