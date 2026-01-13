---
created: 2026-01-13T11:14:45 (UTC +01:00)
tags: []
source: https://emanueledellavalle.org/teaching/big-data-analytics-and-data-science-q2-2018/
author: 
layout: page
title: Big Data Analytics and Data Science, Q2, 2018

img: assets/img/12.jpg
category: 
    - big data
    - data science
related_publications: true
year: 2018
---

## Contents

-   [Introductory Lectures](https://emanueledellavalle.org/teaching/big-data-analytics-and-data-science-q2-2018/#intro)
    -   [Big Data Analytics](https://emanueledellavalle.org/teaching/big-data-analytics-and-data-science-q2-2018/#bda)
    -   [Taming Data Volume](https://emanueledellavalle.org/teaching/big-data-analytics-and-data-science-q2-2018/#tdvo)
    -   [Taming Data Velocity](https://emanueledellavalle.org/teaching/big-data-analytics-and-data-science-q2-2018/#tdve)
    -   [Data Science](https://emanueledellavalle.org/teaching/big-data-analytics-and-data-science-q2-2018/#ds)
    -   ~[Taming Data Variety](https://emanueledellavalle.org/teaching/big-data-analytics-and-data-science-q2-2018/#tdva)~
-   [](https://emanueledellavalle.org/teaching/big-data-analytics-and-data-science-q2-2018/#tech)Technical Lectures
    -   [A deep dive in hadoop](https://emanueledellavalle.org/teaching/big-data-analytics-and-data-science-q2-2018/#hadoop)
    -   [Apache Spark overview analysing Wikipedia logs](https://emanueledellavalle.org/teaching/big-data-analytics-and-data-science-q2-2018/#spark-basics)
    -   [Data science with Apache Spark](https://emanueledellavalle.org/teaching/big-data-analytics-and-data-science-q2-2018/#spark-ds)
    -   [Introduction to Docker](https://emanueledellavalle.org/teaching/big-data-analytics-and-data-science-q2-2018/#docker)
    -   [Deep Learning Theory and Practice with Keras and TensorFlow](https://emanueledellavalle.org/teaching/big-data-analytics-and-data-science-q2-2018/#spark-dl)
    -   [Urban Data Science Hackathon](https://emanueledellavalle.org/teaching/big-data-analytics-and-data-science-q2-2018/#hackathon)
    -   [From SQL to noSQL and back to newSQL](https://emanueledellavalle.org/teaching/big-data-analytics-and-data-science-q2-2018/#noSQL1)
    -   [From SQL to noSQL and back to newSQL](https://emanueledellavalle.org/teaching/big-data-analytics-and-data-science-q2-2018/#noSQL2)

## Introductory Lectures

-   Introduction \[[slide](https://drive.google.com/file/d/1vRNwzqjRheueW4Ca_johyQ_2Ck6wEqlD/view?usp=sharing)\]
    -   What’s Big Data? V_olume_, V_elociy_, V_ariety_ without foresaking _Veracity_
    -   Why? It’s all about _creating value  
        _
    -   How? Paradigmatic shifts enabled by Big Data
-   Netflix and Big Data, a 20 years long success story \[[slide](https://drive.google.com/file/d/1CHKmz8bhbKjYSXKav7m8bP7ZVYddaRJk/view?usp=sharing)\]
-   Vertical vs. Horizontal Scalability \[[slide](https://drive.google.com/file/d/1WP2z9KCk9Y3MVBXXr10foUJTy3bVzioB/view?usp=sharing)\]
-   Horizontal Scalability Business Intelligence in Macy’s \[[slide](https://drive.google.com/file/d/1sRxfxsfzWdH5dm0GeTlFfjxrrnnjclwx/view?usp=sharing)\]

## Taming Data Volume \[25-05-2018\]

-   Scaling Storing Horizontally with NoSQL \[[slide](https://drive.google.com/file/d/1Q-GTCK71ofwjdwCFNKFFKIppcQ-DFE2D/view?usp=sharing)\]
-   Scaling Processing Horizontally with Hadoop \[[slide](https://drive.google.com/file/d/1YUwvt1rRqwjSXcLbnI2fxEBcM4HwjhBp/view?usp=sharing)\]
-   Hiding the details with declarative abstractions (PIG and HIVE) \[[slide](https://drive.google.com/file/d/1MNY9M5OYvOjltKYXfgqkEs4i43nj5AX1/view?usp=sharing)\]
-   Spark: Efficient (100x faster) and Usable (5x less code) Big Data \[[slide](https://drive.google.com/file/d/1iL5q4IIX3KXFUegBnEBaZOYqfMyFTCml/view?usp=sharing)\]
-   Big Data Use Cases \[[slide](https://drive.google.com/open?id=14q2ueUE-naPGG86dOuyTHQFbgzOCIqoC)\]

## Taming Data Velocity \[01-06-2018\]

-   It’s a Streaming World! \[[slide](https://drive.google.com/file/d/1mF0Vy8nVsxFDzV5unAuqJUg2fgET6a_L/view?usp=sharing)\]
-   Taming Velocity with Stream and Complex Event Processing \[[slide](https://drive.google.com/file/d/1a0BN_-8rBQUDYY0XgNs50E86-LBUPgv1/view?usp=sharing)\]
-   Kafka as an example of Stream Processing \[[slides](https://drive.google.com/file/d/1nphnaFDVIIG-9eSgvIgrYGZ7Anld15qJ/view?usp=sharing)\]
    -   Technology perspective
        -   [The Death and Rebirth of the Event Driven Architecture](https://www.confluent.io/kafka-summit-london18/keynote-the-death-and-rebirth-of-the-event-driven-architecture) \[Jay Kreps’ key note at kafka summit 2018\]
        -   [The Present and Future of the Streaming Platform](https://www.confluent.io/kafka-summit-london18/keynote-the-present-and-future-of-the-streaming-platform) \[Neha Narkhede’s key note at kafka summit 2018\]
    -   Kafka sucess stories
        -   [CERN](https://www.confluent.io/kafka-summit-london18/taming-billions-of-metrics-and-logs-at-scale-two-years-with-kafka-as-a-central-data-hub-for-monitoring-at-cern) \[Luca Magnoni’s talk at kafka summit 2018\]
        -   [ING](https://www.confluent.io/kafka-summit-london18/the-evolution-of-kafka-at-ing-bank) \[Timor Timuri + Richard Bras at kafka summit 2018\]

## Data Science \[06-06-2018\]

-   introduction \[slide\]
    -   Why? Get rid of the HiPPO and embrace data-driven decision making!
    -   What? Big Data is crudel oil, Data Science is refining it!
    -   Who? Hacking skills + Math & statistics knowledge + Substantive Experience
    -   How? Statistics + Machine Learning + Visualizations in an agile way
    -   Where? Public safety, Swisscom, ENI
-   Machine Learning overview \[by [Brooke Wenig](https://brookewenig.github.io/)\] \[[slides](https://drive.google.com/file/d/1d9ZyBNjNONnTzw4XB9Li7mch15R7Q5rJ/view?usp=sharing)\]
    -   What? Supervised vs. unsupervised ML
    -   All models are wrong some are useful
    -   K-means as an example of unsupervised ML \[[slides](https://brookewenig.github.io/KMeans.html#/)\]
    -   Examples of supervised ML methods
        -   Logistic Regression for Classification of text as positive vs. negative
        -   Decision Trees for Regression problems (e.g. predicting bike sharing usage)
        -   Random Forests to train model with low bais and low variance

## Taming Data Variety \[~26-06-2018~\]

-   Introduction
    -   The interoperability problem
    -   The standardisation dilemma
    -   Variety cannot be avoided
    -   Embrach variety-proof technologies with smart data & smart machines
-   The long-wave of smart data technologies adoption
    -   The early days of the Semantic Web
    -   The “happy” days of Linked Open Data
    -   The success story of schema.org & Google Knowledge Graph
-   The disruptions of smart machines
    -   From dump machines to smart machines
    -   Deep Learning and its applications
-   Long life Cognitive Computing!
    -   How smart data and smart machines made Watson win Jeopardy
    -   Success stories in Cognitive Computing

## Technical Lectures

## A deep dive in hadoop \[14-06-2018\]

-   Hadoop ecosystem essentials \[[slides](https://drive.google.com/file/d/1Fo2I9Y3rIeo3O-Gl87NcZsS07JdBTC2d/view?usp=sharing)\]
-   Hadoop key blocks: HDFS, YARN, MapReduce, Tez, Pig and Hive \[[slides](https://drive.google.com/file/d/1iWQfiqMGSjdW3dkvnP9RjB8DmErALqof/view?usp=sharing)\]
-   Logical Architecture of a Big Data System \[[slides](https://drive.google.com/file/d/12O_OuScGQ3Ma842UEcS_9mWSsZgv02kc/view?usp=sharing)\]
-   Hands on Hortonworks Data Platform \[[my blob post](http://emanueledellavalle.org/2018/06/17/hands-on-hortonworks-data-platform/)\]
-   More on Technologies:
    -   Core Components: [HDFS 2](https://www.slideshare.net/hortonworks/discover-hdp-22-hdfs-final), [YARN](https://www.slideshare.net/hortonworks/yarn-big-datacampla), [TEZ](https://www.slideshare.net/hortonworks/apache-tez-accelerating-hadoop-query-processing), [slider](https://www.slideshare.net/hortonworks/yarn-ready-webinarslideraug072014)
    -   Data Access: [HIVE 2](https://www.slideshare.net/hortonworks/apache-hive-20-sql-speed-scale-62359247), [Stinger.next](https://www.slideshare.net/hortonworks/discoverhdp22faster-sql-queries-with-hive)
    -   Data Formats: [ORC](https://www.slideshare.net/oom65/orc-files), [Parquet](https://www.slideshare.net/cloudera/hadoop-summit-36479635), [AVRO](https://www.slideshare.net/hadoopusergroup/3-avro-hug20100721)
    -   Data Ingestion: [sqoop](https://www.slideshare.net/cloudera/hadoop-world-2011-integrating-hadoop-with-enterprise-rdbms-using-apache-sqoop-and-other-tools-guy-harrison-quest-software-arvind-prabhakar-cloudera)
    -   Orchestration: [oozie and Ambari workflow editor](https://www.slideshare.net/Hadoop_Summit/breathing-new-life-into-apache-oozie-with-apache-ambari-workflow-manager-95297533)
-   Benchmarks: Tez Improvements \[[slides](https://drive.google.com/open?id=1U6JzkwwaUeGlTHbQL-M6hNhn7hA0d8_l)\] and [Impact of File formats](https://www.slideshare.net/HadoopSummit/file-format-benchmark-avro-json-orc-parquet)
-   Success Stories for [Pig at Twitter](https://www.slideshare.net/kevinweil/hadoop-pig-and-twitter-nosql-east-2009) and [Hive at Facebook](https://www.slideshare.net/dzhou/facebook-hadoop-data-applications)
-   Conclusions: many distributions, even more components, learn them and use the right combination for your use case \[[slides](https://www.slideshare.net/HadoopSummit/hadoop-and-other-animals)\]

## Apache Spark overview analysing Wikipedia logs \[28-06-2018\]

-   Spark as a unifying platform for Data Engineering, Data Analysis and Data Science
-   how to implement simple use cases for Spark using core APIs using Wikipedia logs
-   how to build data pipelines and query large data sets using Spark SQL and DataFrames using English Wikipedia logs
-   Learn about the internals of [Catalyst Optimizer](https://databricks.com/blog/2015/04/13/deep-dive-into-spark-sqls-catalyst-optimizer.html) and [Tugsten](https://databricks.com/blog/2015/04/28/project-tungsten-bringing-spark-closer-to-bare-metal.html)
-   Understand how Spark structured streaming can analyse in real-time Wikipedia edits
-   Understand how GraphFrames can analyse Wikipedia graph (users that edit pages that link other pages)
-   MATERIAL: [notebooks](https://drive.google.com/file/d/1WheHzOjud815MWn_Zb-TcujKvMI8PrGU/view?usp=sharing) for [Databricks](http://community.cloud.databricks.com/)

## Data science with Apache Spark \[05-07-2018\]

-   SparkML: assemble processing, model-building, and evaluation pipelines
-   How to build a simple sentiment mining solution using Logistic Regression and amazon reviews
-   How to predict bike rental counts using Decision Trees
-   Learn how to perform hyperparameter tuning using Random Forests to improve the prediction of bike rental counts
-   Check if you understood by working with Gradient Boosted Decision Trees
-   MATERIAL: [notebooks](https://drive.google.com/file/d/1Rp5aRKwTEeawFd8z28P5VxvkZrcXxgKg/view?usp=sharing) for [Databricks](http://community.cloud.databricks.com/) and [slides](https://drive.google.com/file/d/1TfkpwN-T3CM966xwRJZhStov2OXSQNGr/view?usp=sharing) by  [Brooke Wenig](https://brookewenig.github.io/)

## Docker \[11-07-2018 morning\]

-   Container Basics
-   Docker Images
    -   Architecture
    -   Dockerfile
    -   Docker Hub
-   Docker Services
    -   Compose (single machine)
    -   Swarm Mode (cenni)
-   MATERIAL:
    -   we used [a subset](https://files.gitter.im/cefriel-docker/Lobby/5aeU/cefriel.yml) of the [Container Training.](http://container.training/)
    -   we also used a [gitter.im channel](https://gitter.im/cefriel-docker/Lobby)

## Deep Learning Theory and Practice with Keras and TensorFlow \[11-07-2018 afternoon\]

-   Introduction to Deep Learning: how, why and when it works
-   MNIST Digits Dataset: the dataset for the hands-on
-   Keras: High-Level API for Neural Networks and Deep Learning
-   Hands-on Neural Network with Keras building a “Dense Feed-Forward Shallow” Network
-   Understanding Training using Gradient Descent and Back Propagation
-   Introducing non-linearity: from Sigmoid to ReLU
-   Convolutional Neural Networks: from intuition to a working network for MNIST
-   Recurrent Neural Networks: Networks for Understanding Time-Oriented Patterns in Data
-   Transfer Learning
-   MATERIAL:
    -   [notebooks](https://drive.google.com/file/d/11jgBRfeBEJ6BaZMvQEMr1du1enBJRSIi/view?usp=sharing) for [Databricks](http://community.cloud.databricks.com/)
    -   [playing with Deep Learning in your browser](https://playground.tensorflow.org/)

## Urban Data Science Hackathon \[12-07-2018\]

-   The datasets available: people flows from counting sensors, people presence and demographics from mobile telecom data, free parking, weather, and social media
-   Learning to formulate an Urban Data Science problem
-   Setting a Urban Data Science problem
-   Using methods and techniques learnt in previous days to solve the set problem
-   Presentation of the solutions
-   MATERIAL: [introduction](https://drive.google.com/file/d/1uSBwAAwSJdRUQ5AJrOhLN1S-XVYHA1vU/view?usp=sharing)

## From SQL to noSQL and back to newSQL

### \[06-09-2018\]

-   Brainstorm on which are the requirements of a Database Management System (DBMS), how Relational DBMS address those needs since the ’90s and whether a different approach was possible in the 2000s and is mandatory in the 2010s \[[whiteboard](https://drive.google.com/open?id=1ZujDbmGwk-X5UIfZYcNcd4ofsQBkc4-2)\]
-   A running example we will use across the lecture \[[Entity Relationship diagram](https://drive.google.com/open?id=1LYGYyqNw_NQvSztPy6i7ZiHBbieQ1PDj), [example data](https://drive.google.com/open?id=1EtVGMaqI3-XGrDrF6S6iV6sdQaNl5x14)\]
-   The impediment mismatch problem \[[class diagram of the runnging example](https://drive.google.com/open?id=1gsSEq1INOPjsogctIVjn8qOSfdMvdjMI)\]
-   Documents as transaction boundaries \[[json representation of the running example](https://drive.google.com/open?id=1JEzL_Iagq7lmDIoaT6z4SD1VkiYNO-Qu)\]
-   Numbers to know \[[slide](https://drive.google.com/open?id=1U8akRE93d4DJzjeokqAFP2oFGYCFo3P6)\]
-   key-value stores as memcached and Redis
    -   memcached \[[slides](https://drive.google.com/open?id=1nvWfEdF_W2UK2PojW5FvNS5wi4TiCBv-)\]
    -   hands-on memcached \[[notes](https://drive.google.com/open?id=1lz3N5ANOrSs0UXdEELlRM3rNPRluYCTA)\]
    -   Redis \[[slides](https://drive.google.com/open?id=1vJ7WX-BEcVo7CHsvPzW4cJfuvdE6XWIK)\]
    -   hands-on Redis \[[notes](https://drive.google.com/open?id=1ATUKJ02sgyc-3hgAL1RRudLH5RhXIB2f)\]\[[cheatsheet](https://drive.google.com/open?id=1f_-t3YsEC-A-UhJtX4T76FfTJzOkNGA1)\]\[running example\]

### \[18-09-2018 (am)\]

-   document stores
    -   MongoDB \[[slides](https://drive.google.com/open?id=1owinZAvMy4qnw_tjBUedF3j_W-FhTrwB)\]
    -   hands-on MongoDB \[notes\]
-   scalable column store such as Google BigTable, Hbase and Cassandra \[[slides](https://drive.google.com/open?id=13xd6RzXRZJq7iPmlYlYSK_dFWxIoAm0u)\]
-   graph database \[[slides](https://drive.google.com/open?id=1YsD1K3MlEEYxaHQB3EaVsKEYEExU8Gr-)\]
    -   neo4j and cypher \[[slides](https://drive.google.com/open?id=1wb_zmwvbK0rhu55e0dT4RdFuJnsGtPCp)\]
    -   hands-on neo4j and cypher using neo4j Web interface \[notes\]
    -   RDF and SPARQL \[slides\]
    -   hands-on sparql using dbpedia public sparql end-point \[notes\]

### \[19-09-2018 (pm)\]

-   things left behind from the original plan
    -   back to SQL with newSQL (e.g., VoltDB): it’s always a matter of trade-off
    -   Conclusion: how to choose and what avoid doing \[[slides](https://drive.google.com/open?id=1OShCUY4pQkhOLAx1dDeqFNEpa568ecg9)\]
-   alternatively I can teach more deep learning
