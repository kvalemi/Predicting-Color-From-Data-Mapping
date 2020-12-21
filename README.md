## Project Description

In this project, I trained multiple predictors in a uniform and automated Python pipeline that takes as input RGB data and then maps it to a designated color. I wanted to benchmark multiple predictors so I built a pipeline that trained a Random Forest, KNN, and Naive Bayes on labelled data and then outputted predictions of the test data in the form of a color plot.

## How to Build The Project

1) Ensure labeled dataset is located in script directory (Example of data schema has been included in this repo)

2) To build the script: `python3 weather_clusters.py monthly-data-labelled.csv`

3) The script will output predictions of the training data in the format of a color plot
