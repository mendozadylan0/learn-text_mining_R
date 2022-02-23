# Word Frequency and Sentiment Analysis on 1000 Airbnb Short-term Rentals

**Context:**\
Perform word frequency and sentiment analysis on a subset of review data on 1000 Airbnb short-term rentals within the Boston area using R. 

**Objective:**\
Given the data on the reviews, try to answer the following questions:
- What are the most frequent words and bigrams (after removing stop words and bigrams with stop words)?
- What is the sentiment on the short-term Airbnb rentals? Are they mostly positive, negative, or neutral?
  - For the least "positive" reviews, are they actually "negative" reviews? Meaning that, are the least "positive" reviews the least "positive" because they are genuinely "positive" reviews but simply don't contain enough words that carry a "positive" sentiment in comparison to the other "positive" reviews? Or are they considered the least "positive" reviews because they actually carry a "negative" sentiment.

**Tools Used:**\
R(Tidyverse, Tidytext, Wordcloud, Topicmodels)

**Data Source:**\
- airbnb_reviews_csv: CSV file containing 1000 reviews for a subset of short-term Airbnb rentals within a particular Boston area to be used for our analyses.

