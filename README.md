# Audio Deepfake Detection using FakePrint Features

## Overview:
This project was developed for the Computer Music Representations and Models course of the master’s degree in music and Acoustic Engineering at Politecnico di Milano.
The objective is to distinguish between real and AI-generated audio recordings using spectral analysis and supervised machine learning.
The notebook implements the complete processing pipeline, from audio preprocessing to feature extraction, classifier training and evaluation.

## Workflow
The workflow consists of the following steps:
1.	Load audio recordings using librosa
2.	Compute the Short-Time Fourier Transform (STFT)
3.	Extract FakePrint features from each audio signal
4.	Build the training feature matrix
5.	Train a Logistic Regression classifier
6.	Predict labels on the test set
7.	Evaluate performance using accuracy and a confusion matrix

## Dataset
The dataset contains:
•	training recordings labelled as real or fake
•	an unlabeled test set
•	ground-truth labels used for evaluation
> **note:** The dataset is not included in this repository.

## Author
**Antonio Treviglio**  
M.Sc. Music and Acoustic Engineering  
Politecnico di Milano




