## Data Source

We scraped data from the world news section on the official website of the Guardian （https://www.theguardian.com/international）.

We use the API provided by the Guardian to achieve our goal. (https://open-platform.theguardian.com/explore/)

The Guardian is a British daily newspaper. 


## Metadata 

**The Guardian Corpus Folder**

We created the corpus by randomly choosing 100 per month's world news articles in the Guardian in 2022.
The corpus contains 1200 articles.
They are all saved in txt files with other information of articles in JSON format.
We did not upload this corpus due to copyright.


**metadata and data CSV**


metadata and data CSV file contains information about data and data itself, such as WebTitle, WebUrl, PublishTime, Tags, TagCounts, and Text. We created this file by using pandas. In this file, all articles and tags on one webpage are shown as strings. This is suitable for the next computational analyses.
We did not upload this metadata and data CSV due to copyright.

## Research Objective

In this project, we examine the use of left-wing and right-wing vocabulary in The Guardian's news language to explore the newspaper's ideological inclination.

## files

**Folder: 'analysis process'**

This folder contains files used to analyze the metadata. We utilized Python to augment our metadata CSV with two new classifications: 'continent' and 'countries'. Additionally, we generated a graph showcasing the top 10 countries most frequently discussed by The Guardian. This folder includes both the output graph and the Python code used for its generation. Another file in this folder details our process for calculating the frequency and scores of words identified as left-wing and right-wing.

**Folder: 'country_corpus_improved'**

This folder contains a corpus in which we have categorized articles by country based on the metadata. Each article is assigned to a specific country, facilitating more detailed analysis of The Guardian's coverage across different nations.




