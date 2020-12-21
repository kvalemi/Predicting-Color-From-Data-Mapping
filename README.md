## Project Description

In this project, I trained multiple predictors in a uniform and automated Python pipeline that takes as input RGB data and then maps it to a designated color. I wanted to benchmark multiple predictors so I built the pipeline to train a Random Forest, KNN, and Naive Bayes on labelled data and then outputted predictions of the test data in the form of a color plot.

## How to Build The Project

1) Ensure labeled dataset is located in script directory (Example of data schema has been included in this repo)

2) To build the script: `python3 colour_multiple_predictors.py colour-data.csv`

3) The script will output predictions of the test data in the format of a color plot

## Test Prediction Output:

**Naive Bayes Prediction of Raw RGB**
![](/predictions-0.png)

**Naive Bayes Prediction of RGB Converted to HSV**
![](/predictions-1.png)

**KNN Prediction of Raw RGB**
![](/predictions-2.png)

**KNN Prediction of RGB Converted to LAB**
![](/predictions-3.png)

**Random Forest Prediction of Raw RGB**
![](/predictions-4.png)

**Random Forest Prediction of RGB Converted to LAB**
![](/predictions-5.png)
