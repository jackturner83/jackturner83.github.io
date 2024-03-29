---
title: "Research Proposal"
date:
draft: false
---


## Research Project Overview
Python and a number of libraries, including as tkinter, urllib, BeautifulSoup, pandas, matplotlib, and nltk, were used in my working prototype for a financial news sentiment analysis application.

The prototype is a GUI program that accepts stock ticker symbols as input and generates sentiment readings of news articles pertaining to those equities.

The ticker symbols' labels and entry fields, a button to begin the analysis, a label for the results, and a scrolled text widget to display the results are all included in the application's main window.

The following actions are taken by the program when a user presses the "Analyze" button:

1 - Using the BeautifulSoup library, downloads the HTML news pages for each ticker symbol from a financial news website.
2 - Takes the obtained HTML information and extracts the news headlines, times, and dates.
Utilizing the VADER (Valence Aware Dictionary and sEntiment Reasoner) model offered by the nltk library, analyzes the sentiment of each news headline.
4 - Based on the sentiment ratings of the news headlines mentioning each ticker symbol, the sentiment score of each ticker symbol is calculated.
5 - The scrolled text widget shows the sentiment scores of the news headlines associated with each ticker symbol.

Application, a subclass of tkinter's Frame class, is the only class used in the application, which adheres to the object-oriented programming paradigm. The Application class has methods for creating and initializing GUI widgets, getting news page HTML content, extracting headlines, and analyzing headline sentiment. Different tkinter widgets, including Label, Entry, Button, and ScrolledText, are used to create the GUI widgets.

Overall, the prototype is a straightforward yet useful tool for assessing the tone of financial news articles pertaining to a certain stock. There are certain restrictions, though, such the fact that it only obtains and examines the first five news articles for each company and just shows the sentiment scores of the news headlines without any more research or visualization.

## Motivation

Sentiment analysis is an important area of research because it has many potential applications in areas such as marketing, politics, and social media analysis. However, the accuracy of sentiment analysis on social media data is currently limited, and there is a need to develop more effective algorithms to improve accuracy and enable more informed decision-making.

## Research Gap

Stock market prediction has always been a challenging task, as it involves dealing with complex market behavior and various market conditions. However, with the rise of artificial intelligence (AI) and its potential for analyzing vast amounts of data, there has been increasing interest in using AI for stock market prediction. One of the current knowledge gaps in this field is whether incorporating sentiment analysis and news data can improve the accuracy of AI models for stock market prediction. By performing sentiment analysis on news data, researchers can gain insights into the emotions and opinions of market participants, which can influence market behavior. News data can also provide valuable information that may affect stock prices, which can be captured by integrating it into the AI models. To fill this knowledge gap, researchers can follow a set of steps to investigate whether sentiment analysis and news data can improve the accuracy of AI models for stock market prediction. These steps include collecting and preprocessing historical financial data, performing sentiment analysis on news data, extracting features from the data, training and comparing different AI models, evaluating the best-performing model on a test set of data, and interpreting the results to gain insights.

## Prototype
Python and a number of libraries, including as tkinter, urllib, BeautifulSoup, pandas, matplotlib, and nltk, were used in my working prototype for a financial news sentiment analysis application.

The prototype is a GUI program that accepts stock ticker symbols as input and generates sentiment readings of news articles pertaining to those equities.

The ticker symbols' labels and entry fields, a button to begin the analysis, a label for the results, and a scrolled text widget to display the results are all included in the application's main window.

The following actions are taken by the program when a user presses the "Analyze" button:

1 - Using the BeautifulSoup library, downloads the HTML news pages for each ticker symbol from a financial news website.
2 - Takes the obtained HTML information and extracts the news headlines, times, and dates.
Utilizing the VADER (Valence Aware Dictionary and sEntiment Reasoner) model offered by the nltk library, analyzes the sentiment of each news headline.
4 - Based on the sentiment ratings of the news headlines mentioning each ticker symbol, the sentiment score of each ticker symbol is calculated.
5 - The scrolled text widget shows the sentiment scores of the news headlines associated with each ticker symbol.

Application, a subclass of tkinter's Frame class, is the only class used in the application, which adheres to the object-oriented programming paradigm. The Application class has methods for creating and initializing GUI widgets, getting news page HTML content, extracting headlines, and analyzing headline sentiment. Different tkinter widgets, including Label, Entry, Button, and ScrolledText, are used to create the GUI widgets.

Overall, the prototype is a straightforward yet useful tool for assessing the tone of financial news articles pertaining to a certain stock. There are certain restrictions, though, such the fact that it only obtains and examines the first five news articles for each company and just shows the sentiment scores of the news headlines without any more research or visualization.

## Results through experimentation

My study was initially to understand whether or not sentiment analysis had any role in financial analysis. I wanted to be able to see if sentiment analysis could play a part in making informed decisions regarding the stock market. Although I was successful getting my results of sentiment analysis from financial news articles, I was not able to compare multiple different versions of either stock prediction or traditional financial analysis. This is one way my project could go, as I think it would be really interesting to see whether or not this has any merit in the financial community over other prediction algorithms or just traditional financial analysis.

## Ethical Considerations

1 -Bias: The sentiment analysis model might be unfairly biased in favor of particular news sources or businesses, which could result in an advantage or disadvantage.
2 - Privacy: The sentiment analysis of news items may cause privacy issues for those people who are referenced in the articles.
3 - Misinformation: Inaccurate sentiment analysis model results in misinformation, which may result in poor investing choices.

## Future Work

The future work of this project involves the improvement of the sentiment analysis-based model by using more advanced techniques for sentiment analysis. The project also aims to explore the use of other data sources, such as news articles and financial reports, for predicting stock prices. Additionally, the project aims to investigate the ethical implications of using sentiment analysis for stock price prediction.