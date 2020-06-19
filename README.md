# Exploring COVID-19 Infodemic - Project Overview
* Explored over 1,100 news articles and social network posts on COVID-19 from a variety of new sources.
* Engineered features from the text of each article.
* Compared authenticity of posts between different sources.
* Perfomed Sentiment Analysis using NLP and visualised the attributes.

## Code and Resources Used:
__Python Version:__ 3.7 

__Packages:__ nltk, sklearn, textblob, plotly, pandas, numpy 

__References:__ https://towardsdatascience.com/@actsusanli 

## Data Cleaning:
* First I converted all the rows in 'label' column to uppercase.
* Created a function to read any news article, removed punctuation and changed to lowercase.

## Feature Engineering:
* Got sentiment score of each article.
* Got the length (word count) of each article.

## Exploration:
I got the following insights after exploring the data:
* Most of the true articles seem to be a little shorter than the fake ones, in the data.
* There isn’t a significant difference in terms of sentiment between true news and fake news.
* One stark difference between true and fake news content is that fake news seem to use more often of peoples’ names, this suggest that fake news may be more personal.

## Visualisation:
Some of the visualisations done while exploring:

![alt text](https://github.com/sandeepan1999/Explore-COVID-19-Infodemic/blob/master/article_length.PNG "Article Length")

![alt text](https://github.com/sandeepan1999/Explore-COVID-19-Infodemic/blob/master/sentiment_polarity.PNG "Sentiment Polarity")

*If the [Jupyter notebook](https://github.com/sandeepan1999/Explore-COVID-19-Infodemic/blob/master/Corona%20infodemic.ipynb) doesn't render on Github, please paste the URL of the notebook in this [website](https://nbviewer.jupyter.org/).*
