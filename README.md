# Project-4-Andrew-Yang-Twitter-analysis


Scraping and analyzing the sentiment and topic of tweets related to
Andrew Yang from Arizona.

## Project Pipeline

### Data Acquisition

Using tweepy and getOldTweets3, data was collected and stored in a Mysql
instance on google cloud.

### Data Processing

-   Getting rid of duplicates,retweets,emojis. Tokenizing the tweets,
    > lemmatizing it, and finally vectorize and add stop words and
    > n\_grams.

### Modeling

#### Sentiment analysis

Textblob was used to compute the subjectivity and polarity scores.

#### Topic modeling

LSA, NFM, LDA were attempted, K means clustering was also attempted. NFM
gave the best results.

#### Visualization

TSNE and multidimensional scaling(MDS) were used. Wordcloud was used as
a supplement visualization tool.

## Deliverables

#### Notebooks

NLP\_Unsupervised

#### Presentation

[project\_4.pdf\](/Presentation/project\_4.pdf)

[project\_4.pptx\](/Presentation/project\_4.pptx)
