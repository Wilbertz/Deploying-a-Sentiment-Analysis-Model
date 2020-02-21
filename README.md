# Deploying a Sentiment Analysis Model

## Table of Contents

1. [Installation](#installation)
2. [Directory Structure](#directoryStructure)
3. [Project Motivation](#motivation)
4. [Data Exploration](#exploration)
5. [Features](#features)
6. [Modelling](#modelling)
7. [Results](#results)

## Installation <a name="installation"></a>
This project was written in Python 3.7, using a Jupyter Notebook on Anaconda. 
The relevant Python packages for this project are as follows:

- pandas
- numpy
- nltk
- beautifulsoup4
- html5lib
- torch
- sagemaker_containers

## Directory Structure <a name="directoryStructure"></a>

- Root /

    - README.md  (This readme file)
    - SageMakerProject.ipynb
    - WebAppDiagram.svg
    - serve
        - model.py
        - predict.py
        - requirements.txt
        - utils.py
    - train
        - model.py
        - requirements.txt
        - train.py
    - website
        - index.html
    
 # Project Motivation <a name="motivation" />

The notebook and Python files provided here, once completed, result in a simple web app which interacts
with a deployed recurrent neural network performing sentiment analysis on movie reviews. 
This project assumes some familiarity with SageMaker, the mini-project, Sentiment Analysis using XGBoost, 
should provide enough background.

Please see the [README](https://github.com/udacity/sagemaker-deployment/tree/master/README.md) in the root directory for instructions on setting up a SageMaker notebook and downloading the project files (as well as the other notebooks).

## Data Exploration <a name="exploration" />

## Features 

## Modelling <a name="modelling" />

## Results <a name="results" />