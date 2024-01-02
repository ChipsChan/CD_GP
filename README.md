## Source Data

There is one cover with one title on one webpage on the Guardian. However, some of the covers may be displayed on its webpage along with other related previous reports,
as they are a series of news. The source data we scraped from the Guardian websites contains all the covers shown on one webpage, which could be more than one. 
We include all contents of them when analyzing because they all have effects when they are shown on the same newspaper's webpage.
However， the webpage's title is just the main cover on the last published date instead of the titles of all covers. There is also more than one tag for one webpage's reports.

## Metadata Folder

This folder contains two CSV files: metadata.csv and metadat_list.csv, and a Jupyter notebook. 

**metadata CSV**
metadata CSV file contains information about data, such as WebTitle, WebUrl, PublishTime, Tags, TagCounts, and Text.
In this file, all articles and tags on one webpage are shown as strings. This is suitable for the next computational analyses.

**metadata list CSV**
metadata CSV file contains information about data, such as WebTitle, WebUrl, PublishTime, Tags, TagCounts, and Text.
All articles and tags on one webpage are shown in lists in this file. This is convenient for human readers to distinguish different articles on one webpage.
Or there may be some future analyses that need data in this format.
