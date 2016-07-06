---
title: Jumping into Big Data using Google BigQuery

summary: As we all know Big Data are massive volume of contents. It can be a mixture of structured (e.g. spreadsheets, relational databases) or unstructured data (e.g. images, videos, tweets, web pages)

---

As we all know Big Data are massive volume of contents. It can be a mixture of structured (e.g. spreadsheets, relational databases) or unstructured data (e.g. images, videos, tweets, web pages). Examples of big data are all the videos in YouTube, products in Amazon, and information digested by Google Search. 

Searching and analyzing big data is a hefty task. You will need a lot of processing power and huge storage to store all the contents. Imagine building a search engine that enable searching of contents in the internet and giving a result in a snap. Big Data are characterized by this three main attributes: **volume** (digest a large amount of data), **variety** (data has different forms), and **velocity** (the need to process and understand data fast). 

To eliminate the problem of setting up an infrastructure to store and analyze Big Data, Google built BigQuery.

**BigQuery** is Google's fully managed, petabyte scale, low cost analytics data warehouse. It is part of the services offered under Google Cloud Platform.

BigQuery is serverless, there is no infrastructure to manage and you don't need to hire or be a database administrator to manage your server. Everything is manged and handled by BiqQuery so that you can focus your time analyzing data to fin meaningful insights. 

**How to transfer your existing data to BigQuery?** 
Before we can transfer, we need to prepare the data first. Your files should comply to one of the supported data formats:
* CSV 
* JSON 
* ARVO
* Cloud Data Store
* Excel (Yay! Though they didn't mention support for this. There are ways to push data from Excel to BigQuery)

For data types, only the following are currently supported:
* String
* Bytes
* Integer
* Float
* Boolean
..* For CSV : true or false, 1 or 0 | case insensitive
..* For JSON : true or false | case insensitive
* Record
* Timestamp (Format:YYYY-MM-DD HH:MM:SS)

Once data preparation in finished, you can now transfer your files to BigQuery. Below are the codelabs/tutorials to help you quickstart.
* [Using the Google Cloud Platform Cloud Shell](https://codelabs.developers.google.com/codelabs/cloud-bigquery-load-data/index.html)
* [Using the Web UI](https://cloud.google.com/bigquery/quickstart-web-ui)
* [Using the Command-Line Tool](https://cloud.google.com/bigquery/quickstart-command-line)

To learn more about BigQuery visit [https://cloud.google.com/bigquery/](https://cloud.google.com/bigquery/)

*Note: To access BigQuery and other Google Cloud Platform services, you need to register for an account at cloud.google.com and enable billing. Google offers $300 free credits to first time registrants.*


