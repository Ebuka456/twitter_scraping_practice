# Twitter Scraper and Analyzer

This Python script allows you to scrape tweets from Twitter using snscrape, a more advanced alternative to Tweepy. Additionally, it provides a basic analysis of the collected data to help you identify trends and insights.

## Features
- Scrapes tweets using snscrape
- Extracts and stores tweet metadata such as the tweet ID, timestamp, and more columns
- Performs basic analysis on the collected data, such as calculating the frequency of each hashtag used and generating a word cloud of the most commonly used words
- Outputs the results to a CSV file and a PNG image respectively
- Simple and easy to use

## Requirements
One of the tools and major libraries you would require are
- Python 3.x
- snscrape library (can be installed via pip)
- Pandas library (can be installed via pip)
- Wordcloud library (can be installed via pip)
- Matplotlib library (can be installed via pip)
- Seaborn library (can be installed via pip)

## Installation
1. Clone this repository to your local machine.
2. Install the required libraries by running the following command:
`pip install [library name]`
3. Replace the default query in the script with your own query, or customize the script as needed.
4. Run the script

## Acknowledgments
- [snscrape](https://github.com/JustAnotherArchivist/snscrape) - a Python library that allows you to scrape tweets from Twitter
- [Pandas](https://pandas.pydata.org/) - a library for data manipulation and analysis
- [Wordcloud](https://github.com/amueller/word_cloud) - a library for generating word clouds
- [Matplotlib](https://matplotlib.org/) - a library for creating visualizations in Python

## Limitation
One of the limitation I faced is in the installation of the Wordcloud Library so instead I created a wordcloud using [WordArt](https://wordart.com/), you can also check it. After I created the word cloud, I used Matplotlib to import the image into my notebook.
