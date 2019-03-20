# TCSS 588 Ensemble Project Winter  2019

#### This repository contains multiple the code to train tree and extra tree classifiers for multiple data sets to determine 
relevant genes for those data sets. 

Because the work required for every data set is the same, and I wanted to examine the results as the code ran, I created 
a separate notebook per data set. Therefore, because we worked on 5 data sets, this notebook has 5 data sets.

There is documentation in each notebook also, explaining the steps, and each notebook to summarize, does the following:


a. Loads the training data for either the 1k, 10k, 2.5k or 5k or 100 data set, based on which note book it is.
b. Splits the data using K Folds, with k = 5
c. Trains a tree and extra tree classifier for the 5 folds to calculate the accuracy for every fold and then also report the average accuracy.
d. Determine which genes were most important in each fold.
e. Also every notebook creates data frames to store the results and then creates multiple .csv files to store the results.


### Dependencies

Here are the common dependencies for every notebook:
### Data Files

#### 1. The file  data\\aml.data.RNA.1k.csv - this has the  data
#### 2. The file data\\aml.data.labels.csv  - this file  has the Y values - the class we would like to predict

### Packages

#### This code depends on the following python packages:
#####  os, sklearn, pandas, 
