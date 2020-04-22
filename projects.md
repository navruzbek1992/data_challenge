---
layout: page
title: Projects
permalink: /projects/
---


### [Reverse google image search of objects detected by tensorflow (Tutorial)]

Sometimes we need to perform reverse google image search in order to look up for information about the object in the photo or video.
However, photos could have included other objects as well which makes reverse image search impossible or reduces its accuracy.
I applied tensorflow's already trained models for object detection and for reverse image search. It could be used to extract the part of the photo that contains the object and perform image search.

### [News and stock return relationship (Tutorial)](/projects/news_and_boeing_stocks.html)

What are the main drivers of stock price movement? This is one of the questions of investors and researchers. Fundamental analysis tells us to focus on the market index in order to investigate the stock price movemeny. Since the efficient market hypothesis assumes that prices already incorporated every accessible public news and information. Fortunately, in this data abundant time we can actually gather and analyze news articles quite easily and efficiently. 

This tutorial is about the exploration of the imminent effect of news on stock price movements. First, I scraped news article to gather information about the specific stock. I focused only on Nasdaq.com news section to save time, however, the same analysis could be extended in a larger scale to cover other news sources.

Following the scraping process, text is cleaned thoroughly and analyzed through sentiment analysis (VADER) to investigate if the text contains negative or positive sentiment about the stock. Lastly, I used newly constructed variable to explain stock returns together with market return (empirical CAPM). (Answer codes are given in Python).

[Link for the data](https://github.com/navruzbek1992/data_science_challenges/blob/master/data.zip?raw=true)

***

### [Generalized Lehmann's Alternative Model (Tutorial)](/projects/glam_demonstration.html)

This tutorial is a brief introduction for GLAM. 

***
