# Table of Contents
- [Data Engineering](#1)
- [Data Science](#2)
- [Machine Learning Engineering](#3)
- [Deep Learning](#4)
- [Natural Language Processing](#5)
- [AI for Trading](#6)
- [AI for Healthcare](#7)

<a id='1'></a>
## Data Engineering

### [Music Streaming App Data Engineering](https://github.com/iDataist/Music-Streaming-App-Data-Engineering)
  A music streaming company wanted to analyze the data they collected on songs and user activity on their new music streaming app. The analysis team was particularly interested in understanding what songs users listened to. There was no easy way to query the data to generate the results, since the data resided in a directory of JSON logs on user activity on the app, as well as a directory with JSON metadata on the songs in their app. I created a database and ETL pipeline in both Postgres and Apache Cassandra, designed to optimize queries for understanding what songs users are listening to.

  The company grew their user base and song database, and wanted to move the data warehouse onto the cloud. I built an ELT pipeline that extracts their data from S3, stages them in Redshift, and transforms them into a set of dimensional tables for their analytics team.

  The company grew their user base and song database even more and wanted to move their data warehouse to a data lake. I built an ELT pipeline that loaded data from S3, processed them into analytics tables using Spark, and load them back into S3.

  The company decided to introduce more automation and monitoring to their data warehouse ETL pipelines and came to the conclusion that the best tool to achieve this was Apache Airflow. I created and automated a set of data pipelines. I configured and scheduled data pipelines with Airflow, and then monitored and debugged the production pipelines.

  Key Skills Demonstrated:
  - Data Modeling with Postgres and Apache Cassandra
  - Build the Data Warehouse with S3 and Redshift
  - Build the Data Lake with Spark
  - Automate the Data Pipeline with Apache Airflow

<a id='2'></a>
## Data Science

### [Find Donors for CharityML with Supervised Learning Algorithms](https://github.com/iDataist/Find-Donors-for-CharityML)
  A charity organization would like to build an algorithm to best identify potential donors and reduce overhead cost of sending mail. I evaluated and optimized several different supervised learning algorithms to determine which algorithm will provide the highest donation yield while under some marketing constraints.

  Key Skills Demonstrated:
  - Supervised learning
  - Model evaluation and comparison
  - Tuning models according to constraints

### [Create Customer Segments with Unsupervised Learning Techniques](https://github.com/iDataist/Create-Customer-Segments)
  A company that performs mail-order sales in Germany was interested in identifying facets of the population that were most likely to be purchasers of their products for a mailout campaign. I applied unsupervised learning techniques to organize the general population into clusters, then used those clusters to see which of them comprise the main user base for the company.

  Key Skills Demonstrated:
  - Data cleaning
  - Dimensionality reduction with PCA
  - Unsupervised clustering

### [Create an Image Classifier Using a Deep Neural Network](https://github.com/iDataist/Create-an-Image-Classifier)
  I crated an image classification application using a deep neural network. This application trains a deep learning model on a dataset of images. It then uses the trained model to classify new images.

  Key Skills Demonstrated:
  - PyTorch and neural networks
  - Model validation and evaluation

### [Build a Machine Learning Pipeline to Categorize Emergency Text Messages](https://github.com/iDataist/Build-Pipelines-to-Classify-Messages)
  I built a data pipeline to prepare the message data from major natural disasters around the world, and a machine learning pipeline to categorize emergency text messages based on the need communicated by the sender. Lastly, I deployed the pipelines to create a website app that classify messages.

  Key Skills Demonstrated:
  - ETL Pipeline
  - Machine Learning Pipeline
  - Flask Web App

### [Design a Recommendation Engine](https://github.com/iDataist/Design-a-Recommendation-Engine)
  I analyzed the interactions that users had with articles on the IBM Watson Studio platform, and designed a recommendation engine on new articles that users might like.

  Key Skills Demonstrated:
  - Exploratory Data Analysis
  - Rank Based Recommendations
  - User-User Based Collaborative Filtering
  - Matrix Factorization

<a id='3'></a>
## Machine Learning Engineering

### [Deploy a Sentiment Analysis Model with SageMaker](https://github.com/iDataist/Deploy-a-Sentiment-Analysis-Model-with-SageMaker)
  I built a simple web page which a user can use to enter a movie review. The web page will then send the review off to the deployed recurrent neural network which will predict the sentiment of the entered review.

  Key Skills Demonstrated
  - Text analysis
  - Model deployment via SageMaker
  - APIs for web deployment

### [Create a Plagiarism Detector with SageMaker](https://github.com/iDataist/Create-a-Plagiarism-Detector-with-SageMaker)
  I built a plagiarism detector that examines a text file and performs binary classification, labeling that file as either plagiarized or not depending on how similar that text file is to a provided source text.

  Key Skills Demonstrated
  - Feature engineering
  - Model design and evaluation
  - Model deployment via SageMaker

<a id='4'></a>
## Deep Learning

### [Build a Dog Identification App with Convolutional Neural Networks](https://github.com/iDataist/Build-a-Dog-Identification-App)
  I developed an algorithm that could be used as part of a mobile or web app, which accepts any user-supplied image as input. If a dog is detected in the image, it will provide an estimate of the dog's breed. If a human is detected, it will provide an estimate of the dog breed that is most resembling.

  Key Skills Demonstrated
  - Process the image data
  - Build and train a convolutional neural network
  - Use Transfer Learning

### [Generate Seinfeld Scripts with Recurrent Neural Networks](https://github.com/iDataist/Generate-TV-Scripts-with-Recurrent-Neural-Networks)
  I built a LSTM Recurrent Neural Network (RNN) with PyTorch. I used part of the Seinfeld dataset of scripts from 9 seasons to train the RNN, which can generate a new, "fake" TV script, based on patterns it recognizes in this training data.

  Key Skills Demonstrated
  - Process the text data
  - Build and train a Recurrent Neural Network with PyTorch
  - Optimize hyperparameters

### [Generate Faces with Generative Adversarial Networks](https://github.com/iDataist/Generate-Faces-with-Generative-Adversarial-Networks)
  I built a Deep Convolutional Generative Adversarial Network (DCGAN), which is made of a pair of multi-layer neural networks that compete against each other until one learns to generate realistic images of faces.

  Key Skills Demonstrated
  - Process the image data
  - Build and train a Deep Convolutional Generative Adversarial Network with PyTorch
  - Optimize hyperparameters


<a id='5'></a>
## Natural Language Processing

### [Part of Speech Tagging](https://github.com/iDataist/Part-of-Speech-Tagging)
  I used the Pomegranate library to build a hidden Markov model for part of speech tagging with a universal tagset, and achieved >96% tag accuracy. Hidden Markov models have also been used for speech recognition and speech generation, machine translation, gene recognition for bioinformatics, and human gesture recognition for computer vision.

  Key Skills Demonstrated
  - Process the text data
  - Build and train a hidden Markov model

### [Machine Translation](https://github.com/iDataist/Machine-Translation)
  I built a deep neural network that functions as part of an end-to-end machine translation pipeline. The pipeline accepts English text as input and return the French translation.

  Key Skills Demonstrated
  - Process the text data
  - Build and train a deep neural network with Keras

### [Speech Recognizer](https://github.com/iDataist/Speech-Recognizer)
  I built a deep neural network that functions as part of an end-to-end automatic speech recognition (ASR) pipeline. The model converts raw audio into feature representations, and then turns them into transcribed text.

  Key Skills Demonstrated
  - Extract feature representations from raw audio
  - Build deep learning models to obtain a probability distribution over all potential transcriptions

<a id='6'></a>

## [AI for Trading](https://github.com/iDataist/Trading-with-AI)
I generated alpha signals by performing NLP analysis on Financial Statements, and sentiment analysis with neural network on StockTwits. I then combined signals on a random forest for enhanced alpha. Lastly, I performed portfolio optimization that includes transaction costs.

Key Skills Demonstrated:
- Alpha research and factor modeling
- Portfolio optimization that includes transaction costs
