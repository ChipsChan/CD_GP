## Source Data

There is one cover with one title in one webpage on the Gurdian. However, some of the covers may display on its webpage along with other relating previous reports,
as they are a serie of news. The source data we scraped from the Guardian websites contains all the covers shown on one webpage, which could be more than one. 
We include all contents of them when analyzing, because they all has the affects when they are shown on the same newpaper's webpage.
However，the title of the webpage is just the main cover on the last published date instead of titles of all covers. There are also more than one tags about one webpage's
reports.

## Metadata Folder

This folder contains two csv files: metadata.csv and metadat_list.csv, and a Jupyter notebook. 

**metadata csv**
metadata csv file contains information about data,such as WebTitle, WebUrl, PublishTime, Tags, TagCounts, Text.
In this file, all ariticles and tags on one webpage are shown as strings. This is suitable for the next computational analyses.

**metadata list csv**
metadata csv file contains information about data,such as WebTitle, WebUrl, PublishTime, Tags, TagCounts, Text.
In this file, all ariticles and tags on one webpage are shown in lists. This is convinient for human readers to distinguish different articles on one webpage.
Or there maybe some future analyses need data in this format.
