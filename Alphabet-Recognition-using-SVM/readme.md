# Project Name: Alphabet Recognition using SVM

## Goal :

### The objective is to identify each of a large number of black-and-white rectangular pixel displays as one of the 26 capital letters in the English alphabet. 

### The character images were based on 20 different fonts and each letter within these 20 fonts was randomly distorted to produce a file of 20,000 unique stimuli. 

### Each stimulus was converted into 16 primitive numerical attributes (statistical moments and edge counts) which were then scaled to fit into a range of integer values from 0 through 15. 


### We typically train on the first 16000 items and then use the resulting model to predict the letter category for the remaining 4000.



### Data Set Characteristics: Multivariate

### Attribute Characteristics: Integer

### Task: Classification





## Language: Python

### Libraries Used:
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scikit-Learn

### Model Used: Support Vector Classifier


### Data Link: http://archive.ics.uci.edu/ml/datasets/letter+recognition



