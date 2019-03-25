# Capstone-Project1
# Banknote Authentication

## Description:
This project is about classifying whether a banknote is a counterfeit or an original.
The project uses the data from the dataset at the link https://archive.ics.uci.edu/ml/machine-learning-databases/00267/data_banknote_authentication.txt .
The data is numerical.
There are 5 attributes including the target in the data.
Attribute Information:
1. variance of Wavelet Transformed image (continuous) 
2. skewness of Wavelet Transformed image (continuous) 
3. curtosis of Wavelet Transformed image (continuous) 
4. entropy of image (continuous) 
5. class (integer) 

Target:
class is the target in this dataset as it contains the information whether the banknote is a counterfeit or not.

Data was extracted from images that were taken from genuine and forged banknote-like specimens. 
For digitization, an industrial camera usually used for print inspection was used. 
The final images have 400x 400 pixels. Due to the object lens and distance to the investigated object gray-scale pictures 
with a resolution of about 660 dpi were gained. Wavelet Transform tool were used to extract features from images.


## Installation:
The to get started with Jupyter Notebook is by installing Anaconda.
To get Anaconda, simply:
Download the latest version of Anaconda for Python 3 (ignore Python 2.7) from the link
https://repo.anaconda.com/archive/ .
Install Anaconda by following the instructions on the download page and/or in the executable.
If you are a more advanced user with Python already installed and prefer to manage your packages manually, you can just use pip: *pip3 install jupyter*
To download the ipynb file from GitHub-
* Click on Raw.
* Then, press ctrl+s to save it as .ipynb .
* Open jupyter notebook.
* Go to location where you saved .ipynb file.
* Open file, you will see the code.


## Usage:
The project is of two parts. Part one is about loading the data, data visualisation, feature selection and model selection using sklearn.
This was a beginner's attempt at Machine Learning hence the excitement to explore various accuracy measures in different notebooks.
After observing from implementations in sklearn it was understood that for any given combination of features, KNN classifies better than
Logistic Regression.
However, under the spell of this project being the first I have done, I got a little carried away and trained both the models on all possible combinations of features and made observations in the Banknote Authentication3.xlsx .
