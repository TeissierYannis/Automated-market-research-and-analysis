[![Python](https://img.shields.io/badge/Python_Version-3.9-blue.svg)](https://docs.python.org/3/)
[![Type](https://img.shields.io/badge/Data_Gathering-blue.svg)](#)
[![Type](https://img.shields.io/badge/Machine_Learning-blue.svg)](#)

# Table of Contents

1.  [Project explanation](#project-explanation)
2. [Tree structure](#tree-structure)
3. [Install the requirements](#install-requirements)
4. [Launch the notebook](#launch-notebook)


# Project explanation <a id="project-explanation"></a>

The project begins by allowing the user to select the indices they want to track, such as NASDAQ or the S&P 500, as well as the cryptocurrencies they want to follow, such as Bitcoin or Ethereum. Using this information, the project then scrapes news articles from various sources and identifies those that are relevant to the user's tracking indices.

Once the articles are collected, the Pegasus model is used to summarize the text, creating a condensed version of the article for the user to read. The project also uses the sentiment-analysis pipeline to determine the sentiment of the article, whether it is positive or negative. This provides insight into how the market is feeling about a particular stock or cryptocurrency.

The project then aggregates the sentiment of all the articles related to each stock or cryptocurrency and plots the data on a graph. The graph provides a visual representation of the market sentiment over time, allowing the user to quickly understand trends and patterns.
Additionally, the project allows the user to input their own sentiment about a particular stock or cryptocurrency. This information is then added to the sentiment graph, giving the user a more comprehensive view of the market sentiment.

The project is designed to be highly customizable and can be tailored to meet the needs of individual users. For example, users can adjust the sources from which news articles are collected, the frequency of updates, and the parameters used for sentiment analysis.
In conclusion, this Python project offers a powerful tool for tracking the sentiment of the stock and cryptocurrency markets. With its ability to gather news articles, summarize text, perform sentiment analysis, and generate graphs, users can stay informed about market trends and make more informed investment decisions.

This script includes the following features:
- [X] Article scraping
- [X] Summarization
- [X] Sentiment analysis
- [X] Data saving
- [ ] Data visualization
- [ ] Data analysis
- [ ] Daily update of the data
- [ ] Deployment of the project
- [ ] Web application

# Tree structure <a id="tree-structure"></a>

```sh
.
├── README.md
├── index.ipynb
├── requirements.txt
├── output.csv
```

# Install the requirements <a id="install-requirements"></a>
To install the requirements run the following command:
```sh
pip install -r requirements.txt
```

# Launch the notebook  <a id="launch-notebook"></a>
To launch the notebook run the following command:
```sh
jupyter notebook
```
