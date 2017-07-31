# How_to_do_Sentiment_Analysis
This is the code for 'How to Do Sentiment Analysis' #3 - Intro to Deep Learning by Siraj Raval on Youtube


## Overview

This is the code for using [TFLearn](http://tflearn.org/) to train a Sentiment Analyzer on a set of IMDB [Movie ratings](https://www.kaggle.com/deepmatrix/imdb-5000-movie-dataset). Once trained, given some input text, it will be able to classify it as either positive or negative. The neural network that is built for this is a [recurrent network](https://en.wikipedia.org/wiki/Recurrent_neural_network). It uses a technique called [LSTM](http://colah.github.io/posts/2015-08-Understanding-LSTMs/) which I'll really deep dive into in later videos.

## Dependencies

* tflearn

Use [this](http://tflearn.org/installation/) guide to install TFLearn. Or just use the Amazon Web Services prebuilt [AMI](https://aws.amazon.com/marketplace/pp/B01EYKBEQ0/ref=_ptnr_wp_blog_post) to run this in the cloud


## Usage

Run ``ipython Sentiment Analysis (Must run on a cloud server).ipynb`` in terminal and it should start training. Note this must run on a cload server due to the training rate being so slow.