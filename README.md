# Sentiment_Analysis_of_COVID-19_tweets
Sentiment Analysis on tweets related to COVID-19 by using many techniques.<br/>

In this notebook, many techniques used in the domain of natural language processing, such as language modeling, topic modeling and sentiment analysis,  including data cleaning and normalizing  processes and so on. 
traditional techniques such as **Bag of Words** and **TF-IDF** have been used in addition to applying many deep learning algorithms such as **CNN - LSTM - BI-LSTM - GRU**<br/>
Language modeling was applied based on MLE, which was used to generate new tweets.
Several visualization attached to each model separately using matplotlib, plotly and seaborn, this visualization about classification accuracy and data distribution in the used dataset.

<br/>
Data cleaning process included: 
- 1: Remove URL.
2- Remove Punctuation marks.
(3. ) Remove Stop words.
(4. ) Remove Emojis and Photos.
(5. ) Remove non-ASCII chars.
(6. ) Convert to lowercase.
(7. ) Apply Stemming.
<br/>
Used dataset has been categorized into five classes.
Later, it was converted to binary data to test the best model **BI-LSTM** on it in two classes only (positive and negative).
<br/>
### At the end of the notebook there is a table containing a comparison between the used models
