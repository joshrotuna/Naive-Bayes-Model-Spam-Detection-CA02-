# Naive Bayes Model: Predicting Spam Emails
## Project Description

This project trains a model with 702 emails, equally divided into Spam and Not Spam categories. It then uses the Gaussian Naive Bayes Model to predict the categories of emails in the test data. Finally, it produces the accuracy results scores of the model created. 

## Steps
1. Cleaning and preparing the data
2. Extracting features from every document
3. Training the data and creating preditions
4. Produce accuracy scores

## Requirements

* Python
* Google Colab

## Packages 
import os
import numpy as np
from collections import Counter
from sklearn.naive_bayes import GaussianNB
from sklearn.metrics import accuracy_score
from google.colab import drive
drive.mount('/content/drive')

## Launch

Download *CA02_Naive_Bayes* and open the file in Google Colab.
In Google Drive, create the file structure below:

*/content/drive/My Drive/MSBA_Colab_2020/ML_Algorithms/CA02/Data*


Next, import the *test-mails* & *train-mails* files in previously created folder. 

## Authors

[Joshua Rotuna](https://github.com/joshrotuna)

## License

This project is licensed under the  [MIT](https://choosealicense.com/licenses/mit/)  License.

## Acknowledgements

The project files were provided by Arin Brahma, Loyola Marymount University.
