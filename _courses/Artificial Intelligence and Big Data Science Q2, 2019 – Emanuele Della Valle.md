---
layout: page
title: Artificial Intelligence and Big Data Q2, 2019


img: assets/img/12.jpg
category: 
    - artificial intelligence
    - big data
related_publications: true
year: 2019
---

-   Introduction
    -   [From Big Data to AI via Data Science](https://drive.google.com/open?id=1QY1gCHZtHRtpYEz7Qm5EUkCffyXQMgS8)
        -   Data-driven Decision Making for Data-driven Organizations
        -   What are Big Data, Data Science and AI?
        -   How do Big Data, Data Science and AI support Data-driven Decision Making?
        -   Who is using Big Data, Data Science and AI?
    -   [Success story: The Big Data Science & AI Behind Netflix’s “House of Cards”](https://drive.google.com/open?id=1VRLNGzR185O5ZD9XvP_et2z93Ep1zjKW)
-   Diving into AI
    -   solving problems the AI way
        -   coding vs. machine learning/AI
        -   Gradient Descent as a general procedure
    -   Addressing dynamic pricing with linear regression (supervised machine learning)
        -   what is the relationship is not linear? Polinomial fitting vs. axis transforamtion (a circle is a line in x<sup>2</sup> X y<sup>2</sup>)
    -   Placing shops given distribution of buyers with desired segment solution using k-means (unsupervised machine learning)
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
-   [Final discussion](https://drive.google.com/open?id=1mMOm2eqpE5YsqmmIB8y5STnT8Pklhm9X)
    -   beware confirmation bias
    -   Ethics and legal implications