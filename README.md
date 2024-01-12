# Overview
This repository contains the code and final report submitted as part of the final project for my CS7650 Natural Language Processing class at Georgia Tech. The project, completed by myself and my classmate Jongseok Han, had two primary objectives:
1. Train a classifier that can discriminate between posts made by depressed and non-depressed users of the content sharing platform Reddit
2. Identify common keywords/topics discussed in posts made by depressed users

# Notable Files
1. [data_preprocess.ipynb](data_preprocess.ipynb): Code used for data preprocessing
2. [baselines_and_experiments.ipynb](baselines_and_experiments.ipynb): Code used for all models except the two LSTM-based models
3. [lstm_classifier.ipynb](lstm_classifier.ipynb): Code used for LSTM-based models
4. [Identifying Trends Among Depressed Users of Reddit](Identifying%20Trends%20Among%20Depressed%20Users%20of%20Reddit.pdf): The final report detailing the methodology and results of the project

# Summary of Results
We trained a total of seven classifiers with varying architectures and feature sets, with the highest performing model, an LSTM-based model using unigram and bigram features, achieving an **accuracy of 94.59% and F1: 0.96**. The full results are detailed in Table 1.
![Table 1](https://github.com/athinnyun/reddit-depression-classification/blob/main/Table%201.png?raw=true)

We also identified the most predictive n-grams for posts made by depressed and non-depressed users and generated wordclouds illustrating the most frequent unigrams and bigrams.

![Table 2](https://github.com/athinnyun/reddit-depression-classification/blob/main/Table%202.png?raw=true)

![Table 3](https://github.com/athinnyun/reddit-depression-classification/blob/main/Table%203.png?raw=true)

![Wordclouds](https://github.com/athinnyun/reddit-depression-classification/blob/main/Wordclouds.png?raw=true)

For more details, please read the full report [Identifying Trends Among Depressed Users of Reddit](Identifying%20Trends%20Among%20Depressed%20Users%20of%20Reddit.pdf).
