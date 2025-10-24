We are aiming to do automated handwritten answer sheet grading tool using mainly computer vision, neural networks and machine learning.
Given a dataset of handwritten sentences, the goal is to build a deep learning model capable of accurately transcribing the handwritten text into machine-readable text.
Developing an Optical Character Recognition (OCR) system for handwritten text recognition. 
Succeeding this we use the dataset we created of various statements written by multiple people to verify the model and evaluate them based on correctness using various similarity methods

**Custom made dataset:** This project stands out for its comprehensive dataset that we have manually created of answers which are various statements handwritten by numerous people, accumulating around 450 samples.

**Real time applications:** It will help reduce the workload for teachers and it opens up new possibilities for more comprehensive and faster assessment methods.

**Integration of CRNN Architecture:** This architecture combines the strengths of convolutional neural networks (CNNs) for image feature extraction and recurrent neural networks (RNNs), specifically Long Short-Term Memory (LSTM) units, for sequence modeling.

Our dataset is the iam-sentences dataset with about 16.8k files which we train our model on. It contains a variety of sentences and handwritings.
It has two folders: data(which contains the samples)
    and metadata(which contains the information on and labels of each of the samples)
Source: https://fki.tic.heia-fr.ch/databases/iam-handwriting-database

