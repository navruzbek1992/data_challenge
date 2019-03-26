---
layout: page
title: Projects
permalink: /projects/
---

### [Momentum and mean reversion in stock returns](/projects/project1.nb.html) 

Momentum and mean reversion are commonly employed strategies in investment. But how do we actually find out when stocks change their behavior?

Data is hypothetically developed stock returns that has momentum behaviour in some period and mean reversion in the rest of the period. This challange requires to find exact month and year when stocks' behaviour changeed. Moreover, the average momentum and the mean reversion for all stocks should be estimated. (Answer codes are given in R).

[Link for the data](https://navruzbek1992.github.io/stock-return-analysis/returns_20181228.csv)

***

### [Credit card transactions](/projects/project2.nb.html) 

Is there any useful information or some pattern that we can extract from credit card transactions? This challenge focuses on small transactions data of employees of the State of Oklahoma. As usual, first data is well cleaned and analyzed step by step to get a meaningful insights.

Data consists of transactions made by individuals at different vendors. Data shows inteteresting patterns among credit card holders, such as customers on average become indebted (negative transaction) when purchasing airlines tickets. Moreover, on average the demand for airlines and touristic agencies increased during the data period. This possibly due to the development in tourism and airlines industry around the world. However, data shows several industries where the demand dropped significantly. By checking the credit card data we can see how the consumer demand shifted from old to modern services. (Answer codes are given in R).

[Link for the data](https://navruzbek1992.github.io/stock-return-analysis/res_purchase_2014.csv)

***

### [News and stock return relationship](/projects/news_and_boeing_stocks.html)

What are the main drivers of stock price movement? This is one of the main questions of investors and researchers. Fundamental analysis tells us to focus on the market index in order to investigate the stock since the efficient market hypothesis assumes that prices already incorporated every accessible public news and information. Fortunately, in this data abundant period we can actually gather and analyze news articles quite easily and efficiently. 

This challange is about exploring the imminent effect of news on stock price movement. First, I scrape through web to gather news information about specific stock. I focused only on Nasdaq.com news section to save time, however, the same analysis could be extended in a larger scale to cover other news sources.

Following the scraping through the web, text is cleaned thoroughly and analyzed through sentiment analysis (VADER) to investigate if the text contains negative or positive sentiment about the stock. Lastly, I used newly constructed variable to explain stock returns together with market return (empirical CAPM). (Answer codes are given in Python).

[Link for the data](https://navruzbek1992.github.io/stock-return-analysis/project3.zip)

***


## Contact me

[navruzbek1992@gmail.com](mailto:navruzbek1992@gmail.com)
