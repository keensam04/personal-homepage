---
title: Topic Modelling on a set of Amazon reviews using Restricted Boltzmann Machine
date: 2020-06-26T12:38:27.447Z
draft: false
featured: false
external_link: https://github.com/keensam04/upgrad_pgdmlai/tree/master/TopicModelling_RBM
image:
  filename: rbm.png
  focal_point: Smart
  preview_only: false
---
Topic Modelling is the art and science of identifying the 'latent topics' in a text. It is an unsupervised problem. A set of documents/ corpus are input into the model and the model finds the topics that describe the corpus. Each topic is a distribution over the words that best describe the topic.

Used a Restricted Boltzmann Machine (RBM) to perform topic modelling. The input to an RBM is a bag of words model and the output is the distribution of words in the topics.