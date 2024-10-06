# Naive Bayes Classification with Python

This repository contains a walkthrough and exercises related to Naive Bayes Classification, a simple and effective classification method used in supervised learning. The project demonstrates building and evaluating Naive Bayes models using Python, with applications in blob classification and plant classification (Iris dataset).

## Table of Contents
<ul>
<li>Introduction</li>
<li>Project Structure</li>
<li>Naive Bayes Classification Walkthrough</li>
<li>Exercises</li>
<ul>
<li>Blob Classification</li>
<li>Plant Classification (Iris Dataset)</li>
</ul>
<li>Requirements</li>
</ul>

## Introduction
Naive Bayes is a probabilistic classifier based on Bayes' theorem, assuming independence between features. This repository explores how to implement Naive Bayes for different data types using Gaussian and Multinomial models. Through hands-on exercises, you will learn how to apply Naive Bayes to synthetic and real-world datasets.


## Project Structure
<ul>
<li><mark style="background-color: grey; color: white;">naive_bayes_walkthrough.py:</mark> Step-by-step implementation of Gaussian Naive Bayes, visualizing distributions and evaluating performance on synthetic blob data.</li>
<li><mark style="background-color: grey; color: white;">blob_classification.py:</mark> Implements blob classification using Gaussian Naive Bayes with train-test split.</li>
<li><mark style="background-color: grey; color: white;">plant_classification.py:</mark> Applies Gaussian Naive Bayes to classify plant species in the Iris dataset.</li>
<li><mark style="background-color: grey; color: white;">README.md:</mark> Detailed information on the project, including setup and usage instructions.</li>
</ul>

## Naive Bayes Classification Walkthrough
This walkthrough covers the following key steps:
<ol>
<li>Generating synthetic data with <i>make_blobs</i>.
<li>Fitting a Gaussian Naive Bayes classifier on the data.
<li>Visualizing the data distributions and learned models.
<li>Evaluating the model's performance using metrics such as accuracy, precision, recall, and confusion matrix.
</ol>

## Exercises
Exercise 1: Blob Classification

Write a function <i>blob_classification</i> that:
<ul>
<li>Uses Gaussian Naive Bayes to classify blobs of synthetic data.
<li>Splits the dataset into training and testing sets using <li>train_test_split.
<li>Returns the accuracy score of the model.
</ul>
Exercise 2: Plant Classification

Write a function plant_classification that:
<ul>
<li>Loads the Iris dataset using sklearn.datasets.load_iris.
<li>Trains a Gaussian Naive Bayes model to predict plant species.
<li>Evaluates the model's performance on test data using accuracy score.
</ul>

## Requirements
<ul>
<li>Python 3.x
<li>scikit-learn
<li>numpy
<li>pandas
<li>matplotlib
<li>seaborn