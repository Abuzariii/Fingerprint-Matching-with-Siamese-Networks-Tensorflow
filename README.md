# Fingerprint-Matching-with-Siamese-Networks-Tensorflow

Biometric authentication is the most popular auhtentication method used worldwide. While the existing sensors use traditional algorithms to match fingerprints, deep learning can do much better, specially for cross sensor finger print matching, where sensors find it difficult to match fingerprints of the same subject due to varying feature extraction algorithms.

In this project, I built a CNN based siamese model which uses a triplet loss algorithm defined with squared Euclidean to minimize the distance metric for similar objects and maximize for distinct ones.This model uses an anchor image against a positive and a negative image and outputs the distance between the anchor and the positive and negative images.

The distance between the anchor and positive image is supposed to be very low and that between the anchor and the negative image is supposed to be very high.

This model can work well on all types of sensors and its computation time is in order of a hundred or more miliseconds. So its pretty fast as well compared to regular sensors.

`Dataset`

The dataset used for this project is Sokoto Coventry Fingerprint Dataset or SOCOFing for short, which is a biometric fingerprint database made up of 6,000 fingerprint images from 600 African subjects, designed for academic research purposes, you can find the dataset on Kaggle [here.](https://www.kaggle.com/datasets/ruizgara/socofing)
