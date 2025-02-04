# BSAN_6070_CA02_Spam_eMail_Detection_Naive_Bayes_Classification_Algorithm

## Description

### This is a code that utilizing a Naive Bayes algorithm to classify whether an email is considered spam or not. Utilizing a supervised machine learning algorithm, the emails will be classified based on the number of times uncommon words occur in each email. The model will be trained on 702 emails equally divided into spam and non-spam categories. The algorithm does this by breaking down each individual email into individual words and will begin to break it down based on the words in the email. Once the words list is compiled, the function will eliminate all words that are not alpha-numeric and are one letter. The function will then begin to build a dictionary that is made up of 3000 of the most common words. It will then create a matrix of the individual features (words) and the label that email has (1 for spam, 0 for not spam). These features are then used to help build and train the model which will be used to classify 260 emails into the right category. 

## Necessary Libraries and Versions

* os (Version 3.13.1)
* Numpy (Version 1.18.0)
* Collections (import Counter)
* Pandas (Version 2.2.3)
* Scikit Learn (Version 1.6.1)
* Matplot_lib (Version 3.10.0)
* Scikit Learn (Naive Bayes section with MulitnomialNB function) (Version 1.6.1)
* Scikit Learn (Metrics section with accuracy_score function) (Version 1.6.1)

## Data Set and the Source

### The data set used for this data has two elements in it. These folders are the test emails and the training emails. The data can be found by using the following link (https://drive.google.com/file/d/15Aeig6yJ8C6Qqm5dEtko_SYz9e0DKJDq/view?usp=sharing). It will come zipped at first. Once it is extracted, then the data can be used in the code. This data set was provided by Professor Arin Brahma.

## Source Code Acknowledgement

### Most of the code was provided by Professor Arin Brahma as a part of the second computer assignment for his Introduction to Machine Learning class at Loyola Marymount University. The source code will also be uploaded to this repository so that people can see the raw file. I reused the functions to define the dictionary and extract the features/labels.

## Software Being Used

### Jupyter Notebook


## Installation

### In order to run this code you need to make sure the following:
* Download the .zip folder called "Data" with the emails sorted (test_mails and train_mails)
* Extract all the information from the "Data" .zip folder
* Download the source code file
* Move the file from the "Downloads" folder on your computer to the extracted "Data" folder.
* In the 4th code block, make sure to change the directory strings to match the variable to the right folder
* Make sure that you install all of the necessary libraries and import them at the begining of the code. 
