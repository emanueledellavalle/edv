---
created: 2026-01-13T11:26:56 (UTC +01:00)
tags: []
source: https://emanueledellavalle.org/teaching/bd2sma-html/
author: 
layout: page
title: From Big Data to Social Media Analytics 

img: assets/img/12.jpg
category: big data
related_publications: true
year: 2015
---

#### Introduction (1h)

##### Content

-   Why now?
-   What is Big Data? volume, velocity, variety, veracity, … , and value
-   Paradigm shifts enabled
-   Market Landscape

##### Material

-   [a slightly revised version of the slides](http://emanueledellavalle.org/slides/BD2SMA-2015_01_BigDataIntro.pdf) [\[pdf\]](http://emanueledellavalle.org/slides/BD-2015-1-a_BigDataIntro.pdf) I preseted at the Politecnico di Milano PhD course on [A Multidisciplinary Perspective On Big Data](http://emanueledellavalle.org/Teaching/PhD-course-Big-Data.html)

#### Mastering the Volume Dimension (9h)

##### Operational perspective: the NoSQL world (3h)

###### Content

-   Recalling basic concepts of the relational model
-   NoSQL: basic concepts
-   Key-Value stores
-   Column-family stores
-   Hands-on HBase
-   Document-based stores
-   Hands-on MongoDB (?)
-   Graph-based stores

###### Material

-   the [slides \[pdf\]](https://www.dropbox.com/s/xzqxxa5wrty8938/3-a_noSQLIntro.pdf?dl%253D0) that prof. E. Di Nitto preseted at the Politecnico di Milano PhD course on [A Multidisciplinary Perspective On Big Data](http://emanueledellavalle.org/Teaching/PhD-course-Big-Data.html)
-   HBase
    -   [download from an italian mirror site](http://mirror.nohup.it/apache/hbase/stable/hbase-1.0.1.1-bin.tar.gz)
    -   [getting started using the official guide](http://hbase.apache.org/book.html%2523_introduction)
-   MongoDB
    -   [download from the official site](http://www.mongodb.org/downloads)
    -   [getting started using the official guide](http://docs.mongodb.org/getting-started/shell/)

##### Analytical perspective: from Map Reduce (hadoop) … (2h)

###### Content

-   fundamentals
-   pros and cons
-   evolution
-   eco-system

###### Material

-   [the slides \[pdf\]](https://www.dropbox.com/s/rer5hey1umd4liq/2-c_MapReduceSparkNoAnimation.pdf?dl%253D0) that prof. D. Ardagna preseted at the Politecnico di Milano PhD course on [A Multidisciplinary Perspective On Big Data](http://emanueledellavalle.org/Teaching/PhD-course-Big-Data.html)

##### Analytical perspective: … to Spark (4h)

###### Content

-   Introduction
-   Hands-on: simple Apps
-   Essentials
-   Hands-on Spark SQL
-   Hands-on MLlib, k-means
-   Hands-on GraphX

###### Material

-   a selection of the [slides and software packages](https://s3-us-west-2.amazonaws.com/databricks-meng/usb.zip) (2.1GB!) in the [Spark Summit 2014 Training Archive](https://spark-summit.org/2014/training)

#### Mastering the Variety Dimension (1h30m)

##### Content

-   Variety is unavoidable
-   Embrace variety with semantic technologies
-   Demonstration of ontop

##### Material

-   [my own slides on mastering the Variety dimension of Big Data \[pdf\]](http://emanueledellavalle.org/slides/BD2SMA-2015_05_MasteringVariety.pdf)
-   demonstration of ontop
    -   [my own slides demonstrating of ontop \[pdf\]](http://emanueledellavalle.org/slides/BD2SMA-2015_06_MasteringVarietyOntopDemo.pdf) adapted from a practice session of Politecnico di Milano course on [ICT for Healthcase](http://www.bioinformatics.deib.polimi.it/masseroli/ICT4HC/)
    -   the [ontologies, mappings, queries and relational data \[zip\]](http://emanueledellavalle.org/slides/BD2SMA-2015_06_data.zip) that I prepared for the demonstration
    -   download [Protege 5.0 + -ontopPro-](http://sourceforge.net/projects/ontop4obda/files/ontop-1.15/ontopPro-plugin-with-protege-1.15.0.zip/download): Protege 5.0 bundled with -ontopPro- and the JDBC plugins. This is ready to run package, use the run.sh or run.bat start scripts.
    -   download [H2 + ontop tutorial databases](http://obda.inf.unibz.it/files/h2-ontop-050213.zip): H2 database server bundled with the databases used in the ontop tutorials. Use this to avoid having to install a database to run the tutorials.

#### Mastering the Velocity Dimension and beyond (2h30m)

##### Content

-   It’s a streaming world
-   Information flow processing
-   Hands-on Event Processing Language
-   Volume+Velocity: Hands-on Spark Streaming
-   Velocity+Variety: Stream Reasoning

##### Material

-   [a slightly revised version of the slides \[pdf\]](http://emanueledellavalle.org/slides/BD2SMA-2015_07_Mastering-the-velocity-dimension.pdf) I preseted at the Politecnico di Milano PhD course on [A Multidisciplinary Perspective On Big Data](http://emanueledellavalle.org/Teaching/PhD-course-Big-Data.html)
-   [an EPL-centric version of the slides \[pdf\]](http://emanueledellavalle.org/slides/BD2SMA-2015_07_Hands-on-EPL.pdf) I will present at the Politecnico di Milano PhD course on [Complex Event and Stream Processing](http://streamreasoning.org/courses/scep2015)
-   [an online tool to tryout EPL on esper \[link\]](http://esper-epl-tryout.appspot.com/epltryout/mainform.html)
-   the [stream reasoning Web site \[link\]](http://streamreasoning.org/)

#### The “Traditional” volume-centric use cases and case studies (2 hours)

##### Content

-   The Forrester WaveTM to choose among the vendors
-   Amazon
-   Cloudera
-   Hortonworks
-   MapR technologies
-   IBM Big Insights
-   Microsoft Azure HDInsight

##### Material

-   [my brand new slides](http://emanueledellavalle.org/slides/BD2SMA-2015_08_BigDataUseCasesVolume.pdf) (value the links in the presentation!)

#### Social Media Analytics (5 hours)

##### Content

-   what’s social media?
-   why shuould I care?
-   Personal Social Media Analytics
-   Social Media Analytics for companies
-   So, where’s Big Data?
-   From micropost to (Big) data
    -   Collecting Social Media
    -   Named Entity Recognition
    -   Entity Linking
    -   Sentiment/Opinion extraction
-   Example of Social Media Analytics

##### Material

-   [my brand new slides](http://emanueledellavalle.org/slides/BD2SMA-2015_11_SocialMediaAnalytics.pdf) (value the links in the presentation!)
-   [Example of Social Media Analytics](http://emanueledellavalle.org/slides/BD2SMA-2015-12_Example-of-Social-Media-Monitoring.pdf) from the Stream Reasoning group of Politecnico di Milano and Fluxedo

#### The 5 game changing big data use cases (6 hours)

##### Content

-   Introduction to the 2015 study by IBM Analytics on the five high-value use cases that can be the first step into big data
    -   the study
    -   how to read it

-   Use cases solved with IBM technology as well as with other products offered on the big data market
    -   Big data exploration use case
    -   Enhanced 360-degree view of the customer use case
    -   Security/intelligence extension use case
    -   Operations analysis use case
    -   Data warehouse modernization use case
-   Conclusions

##### Material

-   [my brand new slides](http://emanueledellavalle.org/slides/BD2SMA-2015_09_BigDataUseCasesEmerging.pdf) (value the links in the presentation!)

#### City Sensing case study (2 hours)

##### Content:

-   The digital reflection of our cities is sharpening and it is tracking their evolution with a decreasing delay. This happens thanks to the pervasive deployment of sensors, the wide adoption of smart phones, the usage of (location-based) social networks and the availability of datasets about urban environment.
-   So while data becomes every day more abundant, decision makers face the challenge to increase their capability to create value out of the analysis of this data.
-   This part of the course presents how advance visual analytics, ontology base data access and information flow processing methods can help in making sense of Social Media Streams and Call Data Records from Mobile Network Operators during city scale events. Real-world deployments demonstrate the ability of those methods to advance our ability to feel the pulse of our cities in order to deliver innovative services.

##### Material

-   the [key note](http://emanueledellavalle.org/slides/keynote-DellaValle-BIS2015.pdf) I will give at [BIS 2015](http://bis.kie.ue.poznan.pl/bis2015/)

#### Spark case studies (1 hour)

##### Content

-   Spark at Twitter
-   Hadoop and Spark Join Forces inYahoo
-   Collaborative Filtering with Spark at Spotify
-   Stratio Streaming: a new approach to Spark Streaming!
-   Sharethrough Uses Spark Streaming to Optimize Bidding in Real Time
-   Guavus Embeds Apache Spark into its Operational Intelligence Platform Deployed at the World’s Largest Telcos
-   One platform for all at Conviva: real-time, near-real-time, and offline video analytics on Spark
-   others from Spark summit 2015

##### Material

-   a subset ot the slides in in the [Spark Summit 2014 Training Archive](https://spark-summit.org/2014/training)
