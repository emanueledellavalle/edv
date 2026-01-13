---
layout: page
title: Artificial Intelligence and Big Data Q1, 2019


img: assets/img/12.jpg
category: 
    - artificial intelligence
    - big data
related_publications: true
year: 2019
---

### Introduction

-   [From Big Data to AI via Data Science](https://drive.google.com/open?id=1QY1gCHZtHRtpYEz7Qm5EUkCffyXQMgS8)
    -   Data-driven Decision Making for Data-driven Organizations
    -   What are Big Data, Data Science and AI?
    -   How do Big Data, Data Science and AI support Data-driven Decision Making?
    -   Who is using Big Data, Data Science and AI?
-   [Success story: The Big Data Science & AI Behind Netflix’s “House of Cards”](https://drive.google.com/open?id=1VRLNGzR185O5ZD9XvP_et2z93Ep1zjKW)  
    

### Diving in Big Data

-   Big Data Vertical vs. horizontal scalability \[[slides](https://drive.google.com/open?id=1e1JCh4uwR00YBoALAeqJTJDqYaGcYiZM)\]\[[drawing](https://drive.google.com/file/d/1Jn4NHmNORnsi9ucCjrHZJDJkLoCWrnTz/view?usp=sharing)\]
-   Scaling storage horizontally with K-V pairs \[[slides](https://drive.google.com/file/d/12eZhEDMrb1urk-rARJHRcuNeTChE3TdF/view?usp=sharing)\]\[[drawings](https://drive.google.com/file/d/1uSUOdP6AUUTkByEbbZD4aRlXZL9UYdIp/view?usp=sharing)\]
-   Scaling processing horizontally with MapReduce \[[slides](https://drive.google.com/open?id=14WBb9Tz07STRDDVCJpL4Utl3IMxLAqoS)\]\[[drawing](https://twitter.com/manudellavalle/status/691628048010104832)\]
-   Achieving usability implementing a SQL interfaces on horizontally scalable solutions \[[slides](https://drive.google.com/open?id=1vU044LLlroEzAq93KHcTsvMt8CUO7akS)\]

### Diving into AI

-   solving problems the AI way \[[drawings](https://drive.google.com/file/d/1_5VHVIMqc1ixWvbnFzoMTPQS30SLMDvt/view?usp=sharing)\]
    -   coding vs. machine learning/AI
    -   Gradient Descent as a general procedure
-   Addressing dynamic pricing with linear regression (supervised machine learning) \[[drawings](https://drive.google.com/file/d/1T34GrEZNjznbAyTRTFJZttMlvBL1JYmq/view?usp=sharing)\]
    -   what is the relationship is not linear? Polinomial fitting vs. axis transforamtion (a circle is a line in x<sup>2</sup> X y<sup>2</sup>)
-   Detecting spam emails using Naive Bayes Algorithm \[[drawings](https://drive.google.com/file/d/1vy4YbZ81hlDm5GgPG7o_l5sVc-Ybsli1/view?usp=sharing)\]
-   Recommending Apps based on Decision Trees \[[drawings](https://drive.google.com/file/d/1rGa7RGXVZi7aVHBHGHGy1dEsgwDbgpQt/view?usp=sharing)\]\[[animation](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/)\]
-   Deciding to accept students at a university based on Logistic Regression and Gradient Descent with Log-loss function \[[drawings](https://drive.google.com/file/d/1ksDXGdPN0O5vthHoTX6782siiTznz7Jb/view?usp=sharing)\]  
    When a line is not enough … or the kernel trick of Support Vector Machines \[[drawings](https://drive.google.com/file/d/1rCH6ZhNqDF4dvNlg6i0Ela7FPngMajbS/view?usp=sharing)\]
-   Placing shops given distribution of buyers with desired segment solution using k-means (unsupervised machine learning) \[[drawings](https://drive.google.com/file/d/1rGa7RGXVZi7aVHBHGHGy1dEsgwDbgpQt/view?usp=sharing)\]
    -   does this always work?!? no … [same data -> different cluster algorithm -> different clusters](http://commons.apache.org/proper/commons-math/userguide/ml.html)
-   From a single neuron to deep learning visually using tensorflow playground[https://playground.tensorflow.org](https://playground.tensorflow.org/)
    -   [single neuron classification of two groups that can be separated by a single line](https://playground.tensorflow.org/#activation=sigmoid&batchSize=10&dataset=gauss&regDataset=reg-plane&learningRate=0.03&regularizationRate=0&noise=0&networkShape=1&seed=0.62596&showTestData=true&discretize=false&percTrainData=50&x=true&y=true&xTimesY=false&xSquared=false&ySquared=false&cosX=false&sinX=false&cosY=false&sinY=false&collectStats=false&problem=classification&initZero=false&hideText=false)
    -   [single neuron classification of two groups that can be separated by a circle in x](https://playground.tensorflow.org/#activation=sigmoid&batchSize=10&dataset=circle&regDataset=reg-plane&learningRate=0.03&regularizationRate=0&noise=0&networkShape=1&seed=0.81410&showTestData=true&discretize=false&percTrainData=50&x=false&y=false&xTimesY=false&xSquared=true&ySquared=true&cosX=false&sinX=false&cosY=false&sinY=false&collectStats=false&problem=classification&initZero=false&hideText=false)<sup><a href="https://playground.tensorflow.org/#activation=sigmoid&amp;batchSize=10&amp;dataset=circle&amp;regDataset=reg-plane&amp;learningRate=0.03&amp;regularizationRate=0&amp;noise=0&amp;networkShape=1&amp;seed=0.81410&amp;showTestData=true&amp;discretize=false&amp;percTrainData=50&amp;x=false&amp;y=false&amp;xTimesY=false&amp;xSquared=true&amp;ySquared=true&amp;cosX=false&amp;sinX=false&amp;cosY=false&amp;sinY=false&amp;collectStats=false&amp;problem=classification&amp;initZero=false&amp;hideText=false">2</a></sup> [X y](https://playground.tensorflow.org/#activation=sigmoid&batchSize=10&dataset=circle&regDataset=reg-plane&learningRate=0.03&regularizationRate=0&noise=0&networkShape=1&seed=0.81410&showTestData=true&discretize=false&percTrainData=50&x=false&y=false&xTimesY=false&xSquared=true&ySquared=true&cosX=false&sinX=false&cosY=false&sinY=false&collectStats=false&problem=classification&initZero=false&hideText=false)<sup><a href="https://playground.tensorflow.org/#activation=sigmoid&amp;batchSize=10&amp;dataset=circle&amp;regDataset=reg-plane&amp;learningRate=0.03&amp;regularizationRate=0&amp;noise=0&amp;networkShape=1&amp;seed=0.81410&amp;showTestData=true&amp;discretize=false&amp;percTrainData=50&amp;x=false&amp;y=false&amp;xTimesY=false&amp;xSquared=true&amp;ySquared=true&amp;cosX=false&amp;sinX=false&amp;cosY=false&amp;sinY=false&amp;collectStats=false&amp;problem=classification&amp;initZero=false&amp;hideText=false">2</a></sup>
-   classification of two groups that can be separated by a circle using multiple neurons (each tracing a line)
    -   [basic implementation using sigmoid attivation function (converges in 300 epochs)](https://playground.tensorflow.org/#activation=sigmoid&batchSize=10&dataset=circle&regDataset=reg-plane&learningRate=0.03&regularizationRate=0&noise=0&networkShape=3&seed=0.81410&showTestData=true&discretize=false&percTrainData=50&x=true&y=true&xTimesY=false&xSquared=false&ySquared=false&cosX=false&sinX=false&cosY=false&sinY=false&collectStats=false&problem=classification&initZero=false&hideText=false)
    -   [optimized implementation using ReLU attivation function (converges in 30 epochs)](https://playground.tensorflow.org/#activation=relu&batchSize=10&dataset=circle&regDataset=reg-plane&learningRate=0.03&regularizationRate=0&noise=0&networkShape=3&seed=0.81410&showTestData=true&discretize=false&percTrainData=50&x=true&y=true&xTimesY=false&xSquared=false&ySquared=false&cosX=false&sinX=false&cosY=false&sinY=false&collectStats=false&problem=classification&initZero=false&hideText=false)
-   complex classification
    -   [a sigle layer of neurons hardly works](https://playground.tensorflow.org/#activation=relu&batchSize=10&dataset=spiral&regDataset=reg-plane&learningRate=0.03&regularizationRate=0&noise=0&networkShape=8,1&seed=0.46970&showTestData=true&discretize=false&percTrainData=50&x=true&y=true&xTimesY=true&xSquared=true&ySquared=true&cosX=false&sinX=true&cosY=false&sinY=true&collectStats=false&problem=classification&initZero=false&hideText=false) (even if i[n theory](https://doi.org/10.1007%2FBF02551274) enough neurons do)
    -   [multiple layers (deep learning) easily solves the problem](https://playground.tensorflow.org/#activation=relu&batchSize=10&dataset=spiral&regDataset=reg-plane&learningRate=0.03&regularizationRate=0&noise=0&networkShape=8,8,8,7,2&seed=0.46970&showTestData=true&discretize=false&percTrainData=50&x=true&y=true&xTimesY=false&xSquared=false&ySquared=false&cosX=false&sinX=false&cosY=false&sinY=false&collectStats=false&problem=classification&initZero=false&hideText=false)

### [Final discussion](https://drive.google.com/open?id=1mMOm2eqpE5YsqmmIB8y5STnT8Pklhm9X)

-   beware confirmation bias
-   Ethics and legal implications