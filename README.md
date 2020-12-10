# Presidential-Debate-Twitter-Sentiment-Analysis
Carrying out sentiment analysis of twitter tweets with the hashtag '#PresidentialDebate2020' of Donald Trump and Joe BIden by using Natural language processing and Text Blob frameworks
# Steps Followed
1. Web scraping of recent tweets with the hashtag of '#PresidentialDebate2020' from twitter by using tweepy framework with a twitter developer account
2. Raising flag for each mentioned candidate(Donald Trump or Joe Biden) in the tweet 
2. Preprocessing of text data by removing stopwords and performing lemmatization with nltk and regular expression toolkits
3. Classifying text as positive or negative by calculating its polarity and determined how subjective it is with text blob library
4. Visualized the moving average polarity of both Trump and Biden
