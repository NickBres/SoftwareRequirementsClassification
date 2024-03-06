# Software Requirements Classification Project

## Overview

This project aims to automate the classification of software requirements into functional and non-functional categories using machine learning algorithms. By simplifying the initial stages of software development, this project seeks to enhance project management efficiency and ensure that software quality standards are met.

## Dataset

The dataset comprises 1,000 software requirements initially spread across 14 distinct categories. For practicality and due to the dataset's limited size, these categories have been consolidated into two primary classes: Functional and Non-Functional. The dataset is split into a training set (70%) and a test set (30%) to facilitate model training and evaluation.

## Models

Several machine learning models have been developed and evaluated using Scikit-learn, including:

* Logistic Regression
* Support Vector Classification (SVC)
* K-Nearest Neighbors (KNN)
* Naive Bayes
* Decision Trees (with and without AdaBoost)
* Voting Classifier (combining the above models)
* The models' performance was compared based on accuracy, precision, recall, and the F1 score to identify the most effective algorithm for classifying software requirements.

