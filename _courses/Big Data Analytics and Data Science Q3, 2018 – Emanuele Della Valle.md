---
created: 2026-01-13T11:14:43 (UTC +01:00)
tags: []
source: https://emanueledellavalle.org/teaching/big-data-analytics-and-data-science-q3-2018/
author: 
layout: page
title: Big Data Analytics and Data Science [Q3, 2018] 

img: assets/img/12.jpg
category: 
    - data science
related_publications: true
year: 2018
---

## Contents

-   [Introductory Lectures](https://emanueledellavalle.org/teaching/big-data-analytics-and-data-science-q3-2018/#intro)
    -   [Big Data Analytics](https://emanueledellavalle.org/teaching/big-data-analytics-and-data-science-q3-2018/#bda)
    -   [Taming Data Volume](https://emanueledellavalle.org/teaching/big-data-analytics-and-data-science-q3-2018/#tdvo)
    -   [Taming Data Velocity](https://emanueledellavalle.org/teaching/big-data-analytics-and-data-science-q3-2018/#tdve)
    -   [Taming Data Variety](https://emanueledellavalle.org/teaching/big-data-analytics-and-data-science-q3-2018/#tdva)
    -   [Data Science](https://emanueledellavalle.org/teaching/big-data-analytics-and-data-science-q3-2018/#ds)[](https://emanueledellavalle.org/teaching/big-data-analytics-and-data-science-q3-2018/#tdva)
-   [](https://emanueledellavalle.org/teaching/big-data-analytics-and-data-science-q3-2018/#tech)Technical Lectures
    -   [A deep dive in hadoop](https://emanueledellavalle.org/teaching/big-data-analytics-and-data-science-q3-2018/#hadoop)
    -   [Apache Spark overview analysing Wikipedia logs](https://emanueledellavalle.org/teaching/big-data-analytics-and-data-science-q3-2018/#spark-basics)
    -   [Data science with Apache Spark](https://emanueledellavalle.org/teaching/big-data-analytics-and-data-science-q3-2018/#spark-ds)[](https://emanueledellavalle.org/teaching/big-data-analytics-and-data-science-q3-2018/#docker)
    -   [Deep Learning Theory and Practice with Keras and TensorFlow](https://emanueledellavalle.org/teaching/big-data-analytics-and-data-science-q3-2018/#spark-dl)
    -   [Urban Data Science Hackathon](https://emanueledellavalle.org/teaching/big-data-analytics-and-data-science-q3-2018/#hackathon)
    -   [Introduction to Docker](https://emanueledellavalle.org/teaching/big-data-analytics-and-data-science-q3-2018/#docker)
    -   [From SQL to noSQL and back to newSQL](https://emanueledellavalle.org/teaching/big-data-analytics-and-data-science-q3-2018/#noSQL1)[](https://emanueledellavalle.org/teaching/big-data-analytics-and-data-science-q3-2018/#noSQL2)

## Introductory Lectures

## Big Data Analytics \[05-09-2018 (am)\]

-   Introduction \[[slide](https://drive.google.com/file/d/1HvzbuDHqr4sjr3Cg6YJ8ptF8b2OlR6cv/view?usp=sharing)\]
    -   Data-driven Decision Making for Data-driven Organizations
    -   What are Big Data, Data Science and AI?
    -   How do Big Data, Data Science and AI support Data-driven Decision Making?
    -   Who is using Big Data, Data Science and AI?
-   Netflix and Big Data, a 20 years long success story \[[slide](https://drive.google.com/file/d/1CHKmz8bhbKjYSXKav7m8bP7ZVYddaRJk/view?usp=sharing)\]

## Taming Data Volume \[05-09-2018 (pm)\]

-   Vertical vs. Horizontal Scalability \[[slide](https://drive.google.com/file/d/1WP2z9KCk9Y3MVBXXr10foUJTy3bVzioB/view?usp=sharing)\]
-   Scaling Storing Horizontally with NoSQL \[[slide](https://drive.google.com/file/d/1Q-GTCK71ofwjdwCFNKFFKIppcQ-DFE2D/view?usp=sharing)\]
-   Scaling Processing Horizontally with Hadoop \[[slide](https://drive.google.com/file/d/1YUwvt1rRqwjSXcLbnI2fxEBcM4HwjhBp/view?usp=sharing)\]
-   Hiding the details with declarative abstractions (PIG and HIVE) \[[slide](https://drive.google.com/file/d/1MNY9M5OYvOjltKYXfgqkEs4i43nj5AX1/view?usp=sharing)\]
-   Spark: Efficient (100x faster) and Usable (5x less code) Big Data \[[slide](https://drive.google.com/file/d/1iL5q4IIX3KXFUegBnEBaZOYqfMyFTCml/view?usp=sharing)\]
-   Big Data Use Cases \[[slide](https://drive.google.com/open?id=14q2ueUE-naPGG86dOuyTHQFbgzOCIqoC)\]
-   Horizontal Scalability Business Intelligence in Macy’s \[[slide](https://drive.google.com/file/d/1sRxfxsfzWdH5dm0GeTlFfjxrrnnjclwx/view?usp=sharing)\]

## Taming Data Velocity \[10-09-2018 (am)\]

-   Introduction \[[slide](https://drive.google.com/open?id=1PMZKEYRV_uM7X0n9--6x9-656i7j50BT)\]
    -   How did we get to technologies able to tame velocity?
    -   The database perspective: from RDBMS to DSMS
    -   The event processing perspective: from Publish-Subscribe middlewares to Complex Event Processing
    -   The IT architectural perspective: from Service-Oriented Architecture to Event-driven Architecture
    -   is this only hype?
-   The journey to an event-driven enterprise \[[slides](https://drive.google.com/open?id=1hBRw-DlQWGXrRgT1en9zxrDAEdc-41Ep)\]\[[link to Kakfa Summit 2018 keynote](https://www.confluent.io/kafka-summit-london18/keynote-the-present-and-future-of-the-streaming-platform)\]
    -   1st – streaming awareness and pilot
    -   2nd – early production
    -   3rd – mission critical production
    -   4th – global streaming
    -   5th – central nervous system
-   Introduction to Kafka \[[slide](https://drive.google.com/open?id=161d-zf6nzY73M1mUZ-tsiy8bGeCcjIR2)\]
    -   messaging: topics (regural and compacted), partitions and replicas
    -   stream processing: stream, tables and KSQL
-   Kafka Demo \[[slides](https://drive.google.com/open?id=1g6evlL370MvbPKz2A73rLCQSAJZnhB9M)\]\[[link](https://github.com/confluentinc/quickstart-demos/blob/5.0.0-post/ksql-workshop/ksql-workshop.adoc)\]
-   An experience in using Kafka at small scale \[[slides by Matteo Ferroni](https://www.slideshare.net/MatteoFerroni/1st-italian-kafka-meetup-2017-scan-and-go-with-the-flow-how-i-met-kafka)\]
-   Intereting links to check-out
    -   Massive Online Reasoning \[[MOA](https://moa.cms.waikato.ac.nz/),[SAMOA](https://samoa.incubator.apache.org/)\]

## Taming Data Variety \[10-09-2018 (pm)\]

-   Introduction \[[slides](https://drive.google.com/open?id=1cXWhLj0r-rIVYIGXjPQUz6F2KNdGs5Wf)\]
    -   The interoperability problem
        -   The standardisation dilemma
        -   Variety cannot be avoided
    -   Embrach variety-proof technologies with smart data & smart machines
    -   The long-wave of smart data technologies adoption
        -   The early days of the Semantic Web
        -   The “happy” days of Linked Open Data
        -   The success story of schema.org & Google Knowledge Graph
-   An overview of existing knowledge graphs \[[slides](https://drive.google.com/open?id=1MKgyXxp0R2_6eiRXa2ewEckB6Oy_PCOu)\]
-   Demo of Ontop \[[slides](https://drive.google.com/open?id=1XLKs3ickq_gxsbQr4lAJTLmKm-OKr0uk)\]
    -   ingest a stream
    -   ingest a table
    -   enrich a stream with a table
    -   continuosly analyse the enriched stream
    -   connect elasticsearch and kibana to visualize the analyses in real-time
-   My own research: Stream Reasoning \[[slides](https://drive.google.com/open?id=1xOF3685oTSYVoDcs1ntgq__GSkEdx-tc)\]
-   Interesting links to check-out:
    -   Companies in this area: [Capsenta](https://capsenta.com/), [Spazio Dati](https://spaziodati.eu/it/), [TopQuadrant](https://www.topquadrant.com/), [Cambridge Semantics](https://www.cambridgesemantics.com/), [AtScale](https://www.atscale.com/)

## Data Science \[19-09-2018 (am)\]

-   introduction \[[slide](https://drive.google.com/open?id=1GHcOt4aF49yxTa8SRWO6fxwl1hZbS23t)\]
    -   Why? Get rid of the HiPPO and embrace data-driven decision making!
    -   What? Big Data is crudel oil, Data Science is refining it!
    -   Who? Hacking skills + Math & statistics knowledge + Substantive Experience
    -   How? Statistics + Machine Learning + Visualizations in an agile way
    -   Where? [Public safety](https://www.ted.com/talks/anne_milgram_why_smart_statistics_are_the_key_to_fighting_crime), Swisscom, ENI
-   The main Machine Learning algorithms \[[white board](https://drive.google.com/open?id=1WUAG4zauHsd2cHgZMozHD5DxgyVNPccf)\]
    -   Predicting house prices using Linear Regression and Gradient Descent
    -   Detecting spam emails using Naive Bayes Algorithm
    -   Recommending Apps based on Decision Trees \[[animation](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/)\]
    -   Finding the best location for a shop based on K-means clustering or Hierarchical Clustering
    -   Deciding to accept students at a university based on Logistic Regression and Gradient Descent with Log-loss function
    -   When a line is not enough … or the kernel trick of Support Vector Machines
-   Advance Analytics with Deep Learning
    -   [Hands-on](https://playground.tensorflow.org/) the Linear Perceptron and the linear classification problems it can solve \[[screenshot](https://drive.google.com/open?id=1Xi-pjTZquayjaiRxYS2DXZvm5_Xeb4E6)\]
    -   [Hands-on](https://playground.tensorflow.org/) the Linear Perceptron and the simple non-linear classification problems it can solve \[[screenshot](https://drive.google.com/open?id=1bpYyB6g-nQG0jK4D0M1PVkQHxEuPxMxf)\]
    -   [Hands-on](https://playground.tensorflow.org/) Deep Learning and the complex non-linear classification problems it can solve using sigmoid \[[screenshot](https://drive.google.com/open?id=1zi6HFnq13OrG2X5jMEwlqjN6YCYGj3J8)\], ReLU \[[screenshot](https://drive.google.com/open?id=1VyJwOcyFjcxXw5ySkgZdnYquIvaVeyMA)\] and deep NN \[[screenshot](https://drive.google.com/open?id=1LfTJ0JyTwZS5Z4_dfq5N_OlWlnQdpkef)\]
    -   [Demo](https://transcranial.github.io/keras-js/#/mnist-cnn): how Keras + Tensorflow can classify correctly the MNIST Digits Dataset
    -   [Demo](https://transcranial.github.io/keras-js/#/inception-v3): how Keras + Tensorflow can understand images using Inception V3 model

## Technical Lectures

## A deep dive in hadoop \[11-10-2018\]

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
-   Benchmarks: Tez Improvements \[[slides](https://drive.google.com/open?id=1U6JzkwwaUeGlTHbQL-M6hNhn7hA0d8_l)\] and [Impact of File formats](https://www.slideshare.net/HadoopSummit/file-format-benchmark-avro-json-orc-parquet)
-   Success Stories for [Pig at Twitter](https://www.slideshare.net/kevinweil/hadoop-pig-and-twitter-nosql-east-2009) and [Hive at Facebook](https://www.slideshare.net/dzhou/facebook-hadoop-data-applications)
-   Conclusions: many distributions, even more components, learn them and use the right combination for your use case \[[slides](https://www.slideshare.net/HadoopSummit/hadoop-and-other-animals)\]

## Apache Spark overview analysing Wikipedia logs \[18-10-2018\]

-   Spark as a unifying platform for Data Engineering, Data Analysis and Data Science
-   How to implement simple use cases for Spark using core APIs using Wikipedia logs
-   How to build data pipelines and query large data sets using Spark SQL and DataFrames using English Wikipedia logs
-   Learn about the internals of [Catalyst Optimizer](https://databricks.com/blog/2015/04/13/deep-dive-into-spark-sqls-catalyst-optimizer.html) and [Tugsten](https://databricks.com/blog/2015/04/28/project-tungsten-bringing-spark-closer-to-bare-metal.html)
-   Understand how Spark structured streaming can analyse in real-time Wikipedia edits
-   MATERIAL: [temporary link](https://drive.google.com/open?id=1bb13mOaXTexLIrrokQeqqYltG_U9Vjoe) to the notebooks for [Databricks](http://community.cloud.databricks.com/)  + [this other file](https://drive.google.com/open?id=1BV9uc8R6EYZxBCr9MA9xQUWptdcHrwWf)

## Data science with Apache Spark \[23-10-2018 (am) + 25-10-2018 (am)\]

-   SparkML: assemble processing, model-building, and evaluation pipelines
-   How to build a simple sentiment mining solution using Logistic Regression and amazon reviews \[[white board](https://drive.google.com/open?id=1E4xuqTOqYairtR1_Nu5HFRMxcKjPbXFf)\]  
    
-   How to predict bike rental counts using Decision Trees
-   Learn how to perform hyperparameter tuning using Random Forests to improve the prediction of bike rental counts
-   Check if you understood by working with Gradient Boosted Decision Trees
-   Demo of [K-means||](https://doi.org/10.14778/2180912.2180915) to cluster [Iris flower data set](http://archive.ics.uci.edu/ml/datasets/Iris) \[notebook\]
-   Demo of how to build a movie recommendation engine using [MovieLens dataset](https://grouplens.org/datasets/movielens/) and [Alternating Least Squares](https://link.springer.com/chapter/10.1007/978-3-540-68880-8_32) (ALS) \[notebook\]\[[movie of Monalisa and more scientific insights](https://ruivieira.github.io/a-streaming-als-implementation.html)\]
-   MATERIAL: [notebooks](https://drive.google.com/file/d/1Rp5aRKwTEeawFd8z28P5VxvkZrcXxgKg/view?usp=sharing) for [Databricks](http://community.cloud.databricks.com/) and [slides](https://drive.google.com/file/d/1TfkpwN-T3CM966xwRJZhStov2OXSQNGr/view?usp=sharing) by  [Brooke Wenig](https://brookewenig.github.io/)

## Deep Learning Theory and Practice with Keras and TensorFlow \[6-11-2018\]

-   Demistifying Deep Learning by undersdtanding its core as a simple classifier/regressor  
    
-   Intro to Neural Networks with [Keras](https://keras.io/): [Sequential Models](https://keras.io/models/sequential/), [Compilation](https://keras.io/getting-started/sequential-model-guide/#compilation), Epochs, Loss Visualization, [Activation Functions](http://cs231n.github.io/neural-networks-1/#actfun), [Loss functions](https://keras.io/losses/), [Metrics](https://keras.io/metrics/), [Optimizers](http://ruder.io/optimizing-gradient-descent/) and Batch Size
    -   Understanding Training using Gradient Descent and Back Propagation
    -   Introducing non-linearity: from Sigmoid to ReLU
-   Hands-on Neural Network with Keras building a “Dense Feed-Forward Shallow” Network to predict the house price on the [Boston Housing dataset](https://www.cs.toronto.edu/~delve/data/boston/bostonDetail.html).
-   More on Neural Networks with Keras:   Data Normalization (e.g., [standard scaler](http://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html)), Custom Metrics, Validation data, [callbacks](https://keras.io/callbacks/) (e.g., check pointing and early stopping), and Saving Models
-   Hands-on Neural Network with Keras optimizing the “Dense Feed-Forward Shallow” Network built in previous hands-on to predict the house price on the Boston Housing dataset.
-   Convolutional Neural Networks and [ImageNet](http://www.image-net.org/): from intuition \[[whiteboard](https://drive.google.com/open?id=1f3uT_sQ0xAwM9-nz-4ePIhBAxeHNE2vG)\] to a working network [VGG16 model](https://arxiv.org/abs/1409.1556) and  )
    -   [Understanding Image Kernels](http://setosa.io/ev/image-kernels/)
    -   [learn more](http://cs231n.github.io/convolutional-networks/)
-   Transfer Learning: using [Deep Learning Pipelines](https://github.com/databricks/spark-deep-learning) (Inception V3 and Spark DeepImageFeaturizer) and [Spark Logistic Regression](https://github.com/databricks/spark-deep-learning#transfer-learning)
-   MATERIAL:
    -   [notebooks](https://drive.google.com/open?id=1RfXET6EnpjvJL-iz3l-L4L4avaWrII4Z) for [Databricks.](http://community.cloud.databricks.com/) Make sure you [set-up the cluster](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/6026450283250196/2720471487429801/7409402632610251/latest.html) correctly!
    -   [slides](https://brookewenig.github.io/DeepLearning.html) \[16-48,58-68,88-91\] from [Brooke Wenig](https://brookewenig.github.io/)
    -   [playing with Deep Learning in your browser](https://playground.tensorflow.org/)

## Urban Data Science Hackathon \[14-11-2018\]

-   The datasets available: people flows from counting sensors, people presence and demographics from mobile telecom data, free parking, weather, and social media
-   Learning to formulate an Urban Data Science problem
-   Setting a Urban Data Science problem
-   Using methods and techniques learnt in previous days to solve the set problem
-   Presentation of the solutions
-   MATERIAL: [introduction](https://drive.google.com/open?id=1j0_GEsE4dkPdwP-izVCRriQ16H25HtyH) & link to [gitter channel](https://gitter.im/hackaton-20181114/Lobby)

## Docker \[22.11.2018 (am)\]

-   Container Basics
-   Docker Images
    -   Architecture
    -   Dockerfile
    -   Docker Hub
-   Docker Services
    -   Compose (single machine)
    -   Swarm Mode (cenni)
-   MATERIAL:
    -   we used [a subset](https://drive.google.com/open?id=1oroZOo-dD_apSb3z5c2gYd9FgOeiCqR3) \[pdf\] of the [Container Training.](http://container.training/)
    -   if you cannot install docker, you can try [Docker for Beginners](https://training.play-with-docker.com/) (registration is required)

## From SQL to noSQL and back to newSQL \[22 (pm) / 27 (am) / 29 (am) 11.2018  \]

-   [Gitter channel](https://gitter.im/CEFRIEL2nd/Lobby#) used during the lecture. It contains all the raw examples.
-   Brainstorm on which are the requirements of a Database Management System (DBMS), how Relational DBMS address those needs since the ’90s and whether a different approach was possible in the 2000s and is mandatory in the 2010s \[whiteboard\]
-   A running example we will use across the lecture \[Entity Relationship diagram, example data\]
-   document stores
    -   MongoDB \[[slides](https://drive.google.com/open?id=1owinZAvMy4qnw_tjBUedF3j_W-FhTrwB)\]
    -   [MongoDB Terminal Online](https://www.tutorialspoint.com/mongodb_terminal_online.php)
    -   hands-on MongoDB \[[blog post](http://emanueledellavalle.org/2018/12/02/hands-on-mongodb/)\]
-   graph stores
    -   neo4j and cypher \[[slides](https://drive.google.com/open?id=1wb_zmwvbK0rhu55e0dT4RdFuJnsGtPCp)\]
    -   hands-on Neo4j
-   Key-value stores
    -   Redis \[[slides](https://drive.google.com/open?id=1vJ7WX-BEcVo7CHsvPzW4cJfuvdE6XWIK)\]\[[cheatsheet](https://drive.google.com/open?id=1f_-t3YsEC-A-UhJtX4T76FfTJzOkNGA1)\]
-   Wide column stores
    -   Cassandra \[slides\]
-   Wrapup
    -   Positioning of varioius noSQL solution compared to traditional SQL and new SQL \[whiteboard\]
    -   how to choose and what avoid doing \[[slides](https://drive.google.com/open?id=1OShCUY4pQkhOLAx1dDeqFNEpa568ecg9)\]
