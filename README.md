## Data Source

We scraped data from the world news section on the official website of the Guardian （https://www.theguardian.com/international）.

We use the API provided by the Guardian to achieve our goal. (https://open-platform.theguardian.com/explore/)

The Guardian is a British daily newspaper. 


## Metadata and Data

**The Guardian Corpus Folder**

We created the corpus by randomly choosing 100 per month's world news articles in the Guardian in 2022.
The corpus contains 1200 articles.
They are all saved in txt files with other information of articles in JSON format.
We did not upload this corpus due to copyright.


**metadata and data CSV**


metadata and data CSV file contains information about data and data itself, such as WebTitle, WebUrl, PublishTime, Tags, TagCounts, and Text. We created this file by using pandas. In this file, all articles and tags on one webpage are shown as strings. This is suitable for the next computational analyses.
We did not upload this metadata and data CSV due to copyright.

**metadata CSV**

We uploaded metadata CSV on GitHub, which contains information about data, such as WebTitle, WebUrl, PublishTime, Tags, and TagCounts.

## Research Objective

In the Collecting Data project, we examine the use of left-wing and right-wing vocabulary in The Guardian's news language to explore the newspaper's ideological inclination.

In the Tools& Methods project, we analyze The Guardian's coverage across different nations in the world news section. With the corpus we created, we can generate the most frequently discussed countries and analyze the most frequent words used in these reports of each country.






