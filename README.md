# Analyzing Basketball using Python, Elasticsearch, and Kibana

his demo provides a comprehensive guide on how to:

- Load data into Elasticsearch using Python.
- Write effective queries in Elasticsearch.
- Create insightful dashboards in Kibana.

The focus is on utilizing Celtics and Timberwolves data to showcase these processes.

## Prerequisites

- This demo uses Elasticsearch version 8.14; if you are new, check out our Quick Starts on [Elasticsearch](https://www.elastic.co/guide/en/elasticsearch/reference/current/getting-started.html) and [Kibana](https://www.elastic.co/guide/en/kibana/current/get-started.html).

- Download the latest version of Python if you don’t have it installed on your machine. This example utilizes Python 3.12.1.

- You will use the [nba_api](https://github.com/swar/nba_api) package to get recent statistics about the Boston Celtics, [Jupyter Notebooks,](https://jupyter.org/) and the [Elasticsearch Python Client](https://www.elastic.co/guide/en/elasticsearch/client/python-api/current/getting-started-python.html). While testing this code, I got an error unless I had [pandas](https://pandas.pydata.org/) installed since `nba_data` creates pandas DataFrames.

    To install these packages, you can run the following command.

    ```
    pip3 install nba_api jupyter elasticsearch pandas
    ```

- You will want to load a Jupyter Notebook to work with your data interactively. To do so, you can run the following in your terminal.

    ```
    jupyter notebook
    ```

In the right-hand corner, you can select where it says “New” to create a new Jupyter Notebook.

## Resources
- [How to analyze data using Python, Elasticsearch and Kibana](https://www.elastic.co/search-labs/blog/analyzing-data-using-python-elasticsearch-and-kibana)
- [Intro to Elasticsearch](https://www.youtube.com/watch?v=avxqGSPyKOA)
- [Beginner's Crash Course to Elastic Stack](https://www.youtube.com/watch?v=gS_nHTWZEJ8)

## Getting help

Let us know if you need if this blog post inspires you to build anything or if you have any questions on our [Discuss forums](https://discuss.elastic.co/) and [the community Slack channel](https://communityinviter.com/apps/elasticstack/elastic-community).

