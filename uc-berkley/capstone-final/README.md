# Capstone Project

What causes Cardiovascular Disease?

## Report

### Overview

For this capstone project I will be analyzing a cardiovascular disease dataset from kaggle (https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset) which gives a classification of 0 = No disease and 1 = Has disease

What is cardiovascular disease? It is defined as a group of diseases that impact the heart and blood vessels. Various types of cardiovascular diseases are heart attack, heart failure, stroke, and arrhythmia. These diseases are the most common cause of death worldwide due to poor eating habits (highly proccessed foods, high fructose corn syrup drinks), bad lifestyle habits (smoking, drinking, lack of physical activity)

### Business Understanding

From a business perspective, we want to build a model based on the patient dataset to help future patients better understand their health and the potential risk of cardiovascular disease. By doing so, preventative care measures can be applied.

### Goal

Build different models to see which one is best for data. By looking at the accuracy score of the models we can make a selection.

### Initial Findings

After testing multiple models, I can conclude that Ensemble techniques is the best approach for building a model on our data and making the best accurate predictions (refer to confusion matrix plots in jupyter notebook)

### Other Analysis

One thing that can be done, is to split the data into male and female and build two models based on sex (as seen in the plots below). We know that there are biological differences between men and women, measurements such as height, weight, bone density, are example of differences between the two genders. If we split the data, I hypothesize that the accuracy of the two models will be much higher and the rate of false positive and false negative will be lower (refer to confusion matrix plots in jupyter notebook).  

#### Link to plots

Creating plots are a great way to have a visual representation, and it tells us a story about the data.

![alt text](https://github.com/seyfullah642/ml-and-ai/blob/main/uc-berkley/capstone-final/height_distr.png)

![alt text](https://github.com/seyfullah642/ml-and-ai/blob/main/uc-berkley/capstone-final/age_distr.png)

![alt text](https://github.com/seyfullah642/ml-and-ai/blob/main/uc-berkley/capstone-final/weight_distr.png)

![alt text](https://github.com/seyfullah642/ml-and-ai/blob/main/uc-berkley/capstone-final/systolic_bp_distr.png)

![alt text](https://github.com/seyfullah642/ml-and-ai/blob/main/uc-berkley/capstone-final/diastolic_bp_distr.png)

#### Link to notebook

[notebook link](https://github.com/seyfullah642/ml-and-ai/blob/main/uc-berkley/capstone-final/capstone.ipynb)