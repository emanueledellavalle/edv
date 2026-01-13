---
created: 2026-01-13T11:26:40 (UTC +01:00)
tags: []
source: https://emanueledellavalle.org/teaching/data-streams-big-data-and-analytics-3-days-q4-2018/
author: 
layout: page
title: Data Streams, Big Data and Analytics (3 days), Q4, 2018

img: assets/img/12.jpg
category: big data
related_publications: true
year: 2018
---

## An introduction to Big Data technologies (15.11.2018)

-   Introduction \[[slide](https://drive.google.com/file/d/1HvzbuDHqr4sjr3Cg6YJ8ptF8b2OlR6cv/view?usp=sharing)\]
    -   Data-driven Decision Making for Data-driven Organizations
    -   What are Big Data, Data Science and AI?
    -   How do Big Data, Data Science and AI support Data-driven Decision Making?
    -   Who is using Big Data, Data Science and AI?
-   Netflix and Big Data, a 20 years long success story \[[slide](https://drive.google.com/file/d/1CHKmz8bhbKjYSXKav7m8bP7ZVYddaRJk/view?usp=sharing)\]
-   Scaling Storing Horizontally with HDFS \[[whiteboard](https://drive.google.com/open?id=1BPEEqB4qW60UM9uQUf4rQK-GppNi6s5f)\]
-   Scaling Processing Horizontally with Hadoop \[[whiteboard](https://drive.google.com/open?id=11dk_aLhz6hkoQNODmlXJMwHAhIwWsfLD),[slide](https://drive.google.com/file/d/1YUwvt1rRqwjSXcLbnI2fxEBcM4HwjhBp/view?usp=sharing)\]
-   Vertical vs. Horizontal Scalability \[[slide](https://drive.google.com/file/d/1WP2z9KCk9Y3MVBXXr10foUJTy3bVzioB/view?usp=sharing)\]
-   Enabling data analytics  \[[slide](https://drive.google.com/file/d/1MNY9M5OYvOjltKYXfgqkEs4i43nj5AX1/view?usp=sharing)\]
    -   hiding the MapReduce details using PIG and HIVE on Tez
    -   choosing optimized file formats (ORC and Parquet)
-   Benchmarking speed ups \[[slides](https://drive.google.com/open?id=1U6JzkwwaUeGlTHbQL-M6hNhn7hA0d8_l)\]
-   Logical Architecture of a Big Data System \[[slides](https://drive.google.com/file/d/12O_OuScGQ3Ma842UEcS_9mWSsZgv02kc/view?usp=sharing)\]
-   Horizontal Scalability Business Intelligence in Macy’s \[[slide](https://drive.google.com/file/d/1sRxfxsfzWdH5dm0GeTlFfjxrrnnjclwx/view?usp=sharing)\]

## Spark: a unified engine to tame volume and velocity (26.11.2018)

-   Spark: Efficient (100x faster) and Usable (5x less code) Big Data \[[slide](https://drive.google.com/file/d/1iL5q4IIX3KXFUegBnEBaZOYqfMyFTCml/view?usp=sharing)\]
-   Overview of Spark internals
    -   Cluster Architecture
    -   How Spark schedules and executes jobs and tasks
    -   The Catalyst query optimizer
-   In-depth presentation of Spark SQL and DataFrames:
    -   reading in DataFrames from CSV with and withoud schema inference
    -   writing DataFrames as Parquet and Tables
    -   Spark SQL and the role of caching
    -   Data Aggregation, Column Operations, date/time funtions
    -   Use of the Spark UI to analyze behavior and performance
-   Spark Structured Streaming
    -   Sources and sinks
    -   Structured Streaming APIs
    -   Windowing & Aggregation

## Kafka: a distributed streaming platform (4.12.2018 am)

-   Introduction to Kafka \[[slide](https://drive.google.com/open?id=161d-zf6nzY73M1mUZ-tsiy8bGeCcjIR2)\]
    -   messaging: topics (regural and compacted), partitions and replicas
    -   stream processing: stream, tables and KSQL
-   Kafka Demo \[[slides](https://drive.google.com/open?id=1g6evlL370MvbPKz2A73rLCQSAJZnhB9M)\]\[[link](https://github.com/confluentinc/examples/blob/5.0.1-post/ksql-workshop/ksql-workshop.adoc)\]
-   An experience in using Kafka at small scale \[[slides by Matteo Ferroni](https://www.slideshare.net/MatteoFerroni/1st-italian-kafka-meetup-2017-scan-and-go-with-the-flow-how-i-met-kafka)\]

## Analytics with SparkML:  (4.12.2018 am)

-   understanding sentiment analytics on [IMDB data](https://www.imdb.com/interfaces/) as a classification problem \[[whiteboard](https://drive.google.com/open?id=1MDOkHJHKXfmcFD8789YwxeisOPm6lwSw)\]
    -   How to build machine learning pipelines for supervised learning
    -   Use transformers to perform pre-processing on a dataset prior to training
    -   Train analytical models with Spark ML’s DataFrame-based estimators including Logistic Regression and Decision Trees
    -   Evaluate a classification model performance using a confusion matrix
-   understanding predictive analysis of [bike rental counts](http://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset) as a regression problem using Decision Trees \[[whiteboard](https://drive.google.com/open?id=1K0YqA-gTC5GZU3MmCEesrE7G_LVQE9Oy)\]
    -   hands-on building a pipeline
    -   Evaluate a regression model performance using a confusion matrix
    -   Model complexity, underfit and overfit
-   Learning to tune hyperparameters via cross-validation and grid search applying Random Forests to bike rental counts \[[whiteboard](https://drive.google.com/open?id=1pUuYPyPJJkXLkn8DlN2JCUZ2S_sPmsq3)\]
