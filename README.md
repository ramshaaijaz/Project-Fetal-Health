# Project-Fetal-Health
**Author**: Ramsha Aijaz
## Description
This data look at fetal classification across three categories i.e "normal", "suspect" and "pathological". We try to classify the dataset according to different machine learning models. This project is essential because it uses machine learning models to asses the fetal health risk and from a policy perspective, this is beneficial in planning healthcare iniatives, and the measures healthcare sectors can take to predict disease incidence. I used 6 classification models namely, Random Forest, KNN, XGBoost, SVN, Gaussian Classifier and Decision trees. I faced some challenges in implementing XGBoost because it was giving an error, when I was building the confusion matrix, however I finally imported XGBoost Classifier and that solved the issue at hand. 
## Data
The data is taken from kaggle dataset https://www.kaggle.com/andrewmvd/fetal-health-classification, and contains 2,126 values with 22 variables. I have implemented data mining methods to clean duplicates, so that they do not interfere with the accuracy of the model. 
## How to use the code
This file can be downloaded and run on google colab or a local python program. You will have to rerun all the import packages and the codes to get the desired results. 
A little intro about the installing packages. 

$ import numpy
$ import pandas
$ from sklearn cluster, datasets, metrics

How to read the file?
$!gitclone https://github.com/ramshaaijaz/Fetal-Health
$ pd.read.csv command and copied the file's path
````````````
Then, I started reading the data to run various commands like df.describe to understand the description of the model, and made different boxplots to see the outliers etc. 
After that, I ran commands for different machine learning models but before that I split the data into train test and scaled and normalized the data to resolve any imbalances in the dataset. 
.................
## Results
After all the models were applied, XGBoost showed the highest accuracy at 0.94, followed by random forest 0.93. I also ran confusion matrix to make sure we are not only deluded by the accuracy scores

