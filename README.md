# HAR

Human Activity Recognition using UCI Dataset

## Downloading Dataset

Download from [here](https://archive.ics.uci.edu/ml/machine-learning-databases/00240/)


### Getting Started

Rename the dataset folder to UCI_HAR_dataset to sync it with the code
The dataset folder must be in the folder of the repository



## About the dataset

Feature names are present in 'UCI_HAR_dataset/features.txt'

Train Data:
- 'UCI_HAR_dataset/train/X_train.txt'
- 'UCI_HAR_dataset/train/subject_train.txt'
- 'UCI_HAR_dataset/train/y_train.txt'
Test Data:
- 'UCI_HAR_dataset/test/X_test.txt'
- 'UCI_HAR_dataset/test/subject_test.txt'
- 'UCI_HAR_dataset/test/y_test.txt'

The raw time series data will be present in a folder "Inertial Signals" inside the train/test sub-folder

## Summary

The dataset contains 561 man-engineered features that were created by domain experts, from the raw data obtained of various smartphone sensors.
Classical ML models are built on these 561 engineered features.

The dataset also contains raw time series data from the sensors. Since these raw data proves to be inefficient for working of classical ML models, we use the engineered features.

#### Notebook 1. HAR_EDA.ipynb explains the dataset and explores the data

#### Notebook 2. HAR_PREDICTION_MODELS.ipynb builds various models/trains them and compares the test results.

DEEP LEARNING models prove to be efficient enough to work on the raw data and produce impressive results without the help of domain experts generated features.
A LSTM working model processing on raw data will be uploaded soon to show the above results.
