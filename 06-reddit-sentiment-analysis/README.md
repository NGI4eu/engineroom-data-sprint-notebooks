# EngineRoom: Sentiment Analysis
Sentiment analysis applied to some words of the Reddit dataset.

The English LIWC dictionary is needed to run a part of this Jupyter. For just seeing and playing with the last visualization, it is not needed.

There is a folder ("data"), where you can find a file with the list of the keywords analyzed: reddit_keywords.txt

There is also a notebook available (Sentiment_Analysis_LIWC.ipynb) with the methods to plot the visualizations. We show an example below of the available visualizations.


```
plot_multibar_sentiment(['gdpr', 'fake news','intellectual property' ])
```

![alt text](https://github.com/NGI4eu/engineroom-sentiment_analysis/blob/master/images/visualization_sentiments.png)

The X-axis shows the different categories of sentiments (past, present, future, swear, affect, positive emotions, negative emotions, anxiety, anger, sadness and discrepancy), and the Y-axis shows the percentage of words that fall in that category. 


```
plot_monthly_multiple_sentiments(['deletefacebook', 'brain-computer interface', 'autonomous weapon', 'competition law', 'hate speech', 'killer robot', 'metoo', 'digital surveillance', 'altright', 'freedom of speech'])
```
![alt text](https://github.com/NGI4eu/engineroom-sentiment_analysis/blob/master/images/reddit_monthly_multiple_sentiments.png)

The X-axis shows the month, and the Y-axis shows the option that you have selected in the tab. 

The available options are:
- num_comments: Number of comments avaluated for each of the keywords.
- num_deleted: Number of deleted comments by the author.
- num_removed: Number of removed comments by Reddit moderators.

 And the following emotions or language dimensions: 
 
 ![alt text](https://github.com/NGI4eu/engineroom-sentiment_analysis/blob/master/images/table_sentiments.png)
 
 


