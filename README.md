# HAR
Human Activity Recognition using UCI Dataset

-> Download the dataset from the link : https://archive.ics.uci.edu/ml/machine-learning-databases/00240/ into the repository folder.
-> Rename the dataset folder to UCI_HAR_dataset to sync it with the code.
-> The dataset contains 561 man-engineered features that were created by domain experts, from the raw data obtained from various sensors.
-> Classical ML models are built on these 561 engineered features.
-> Notebook 1. HAR_EDA.ipynb explains the dataset and explores the data
-> Notebook 2. HAR_PREDICTION_MODELS.ipynb builds various models/trains them and compares the test results.

-> To show the strength of DL Models, we will build DL Models on the raw time series data and not on the man-engineered features.
-> The raw time series data will be present in a folder "Inertial Signals" inside the train/test sub-folder.
-> The LSTM working model processing on raw data will be uploaded soon.
