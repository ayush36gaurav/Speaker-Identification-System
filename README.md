# Speaker-Identification-System

The Speaker Identification System is designed to identify a speaker based on previously available training dataset.

The dataset used for this project is available on Kaggle at: https://www.kaggle.com/datasets/kongaevans/speaker-recognition-dataset

The system uses MFCC to extract features from the voice samples then uses Gaussian Mixture Modelling for each speaker. It uses KMeans Clustering to find the optimal number of components for each speaker's GMM.

The overall accuracy of the Speaker Identification System on the test data is 99.75%.
