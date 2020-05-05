# COIN
## Contextual Outlier INterpretation
In this package, we implement the Contextual Outlier INterpretation (COIN) method that aims to explain the 
abnormality of existing outliers spotted by detectors.

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Data Set](#data-set)
* [Reference List](#reference-list)
* [Setup](#setup)

## General info
This framework is based on the COIN paper([Source](https://arxiv.org/pdf/1711.10589.pdf)).An outlier is defined as a data point which is very different from the rest of the data based on some measures. Nowadays, the outlier detection method is frequently used in many applications as fraud detection, credit card fraud, etc... enabling interpretability could benefit outlier detection and analysis in several aspects because interpretation helps to bring together detecting outliers and identifying domain-specific anomalies, it can intervene in the evaluation phase to complete the current metrics that are being used and then do not provide the same performance on different types of applications.
To tackle the challenges, this framework is designed to provide explanations for outliers identifed by detectors. The interpretability for an outlier is achieved from three aspects such as outlierness score, attributes that contribute to
the abnormality, and contextual description of its neighborhoods.
	
## Technologies (Dependencies)
Project is created with:
* python version: 3.0
* Scikit-Learn version: 0.20.3
* Numpy version ...
* etc ...


## Data Set
The real-world datasets used in this experiments include Wisconsin Breast Cancer (WBC) dataset ([Here](https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+(original) "visit the page")). 
## Reference Lists
#### Outlier detection
* Local Outlier Detection (LOF) ([Source](https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.LocalOutlierFactor.html))
* Isolation Forest ([Source](https://docs.seldon.io/projects/alibi-detect/en/latest/methods/iforest.html "visit the page"))

#### Classifier
* Support Vector Machine (svm)
* KMeans (...)
* K-Nearest Neighbors (KNN) (...)

## Setup
To run this package, install it locally using ...

```
```