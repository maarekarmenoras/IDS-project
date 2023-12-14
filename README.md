# Credit Card Fraud Detection With Machine Learning

This is a project for the course Introduction to Data Science at the University of Tartu by Enriko Kroon, Maare Karmen Oras and Karoliina Valge. The aim of it is to put our data science skills to the test to train a model to detect fraudulent credit card transactions. We chose this topic because credit card fraud is a very relevant issue in the world right now, especially online.

# Data

The data used in this project is from <a href=https://www.kaggle.com/datasets/kartik2112/fraud-detection>Credit Card Transactions Fraud Detection Dataset</a> by Kartik Shenoy on Kaggle. In case you want to run the notebooks in this repo, it is first recommended to <b>download the datasets from Kaggle</b> and add them to the /data folder, as we've previously had issues with large file storage on GitHub. It's also noteworthy that this is a synthetic dataset, because real datasets regarding credit card fraud are either confidential or anonymized to protect the identities of card-holders.

# Usage

This project is mainly split between 2 files, data_understanding.ipynb and project_file.ipynb. The former consists of data analysis and the latter contains the data preprocesssing and model training for this project. In the beginning of both files are the imports, which need to be installed if they do not already exist on your machine. If the datafiles are present in the correct folder and the necessary libraries are installed, both notebooks should be able to run from start to finish without issues. However, considering that we have used grid search on two occasions, project_file.ipynb can take a few hours to finish if they are run in their current state. We are looking into adding model saving and loading to cut down on run time in the future.
