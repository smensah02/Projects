# ![]() Project 2: Web APIs & Classification

### Description

Webscraping, APIs, and Natural Language Processing (NLP)

For this project, the goal is two-fold:
1. Using Reddit's API to collect posts from two subreddits.
2. Use NLP to train a classifier on which subreddit a given post came from. This is a binary classification problem.


#### About the API

Reddit's API is fairly straightforward. For example, if I want the posts from [`/r/boardgames`], all I have to do is add `.json` to the end of the url: https://www.reddit.com/r/boardgames.json.

For my project, I scrapped [`/r/AskHistorians/`] (https://www.reddit.com/r/AskHistorians) and [`/r/todayilearned`] (https://www.reddit.com/r/todayilearned)


### Requirements

- Scrape and prepare your data using the `requests` library.
- **Create and compare two models**. A random forest any other classifier such as: logistic regression, KNN, SVM, etc.
- A Jupyter Notebook with analysis for a peer audience of data scientists.
- An executive summary of the results found.
- A short presentation outlining process and findings for a semi-technical audience.


#### Data Collection

Data is collected from external sources through API's or scraping where applicable.  Data is collected and parsed using appropriate Python modules and effective Python code.

---

### Why this project?
This project covers three main concepts: Classification Modeling, Natural Language Processing and Data Wrangling/Acquisition.

Part 1 of the project focuses on **Data wrangling/gathering/acquisition**. This is a very important skill as not all the data you will need will be in clean CSVs or a single table in SQL.  There is a good chance that data come from some unstructured/semi-structured sources; when possible, requesting information from an API, but often scraping it because they don't have an API (or it's terribly documented).

Part 2 of the project focuses on **Natural Language Processing** and converting standard text data (like Titles and Comments) into a format that allows us to analyze it and use it in modeling.

Part 3 of the project focuses on **Classification Modeling**.  some means of assessment and preprocessing associated with classification.   
