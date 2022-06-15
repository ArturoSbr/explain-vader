# Explaining VADER

## About this project
This project sets up a simple web-app that allows users to explain the most influential words that drove VADER, a popular NLP model, to make a given prediction.

## What is VADER?
VADER is a (very) popular pre-trained sentiment analyzer. It is a simple NLP model able to extract the negative, neutral and positive intensities of content posted on social media.

## How does it work?
NLP is a challenging task. It involves highly-complex models that sacrifice interpretability in favor of prediction accuracy.

LIME is a relatively new method for explaining the predictions made by any kind of model. The [original paper](https://arxiv.org/abs/1602.04938) offers a comprehensible review of its application to tabular, image recognition and NLP models.

This project focuses on LIME for NLP models. In essence, LIME makes many slight modifications to the text passed by the user and fits an interpretable model on these perturbed instances in order to come up with an interpretable local explanation.