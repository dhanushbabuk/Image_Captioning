# Image Captioning With LSTM And Vanilla RNN

## Introduction

This project demonstrates image captioning using two different types of Recurrent Neural Networks (RNNs): Long Short-Term Memory (LSTM) and Vanilla RNN. Image captioning involves generating a textual description for a given image, a complex task that requires understanding both the content of the image and generating coherent text.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Examples](#examples)
- [Model Architecture](#model-architecture)
- [Dataset](#dataset)
- [Training](#training)
- [Evaluation](#evaluation)
- [Results](#results)


## Installation

To get started with this project, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/image-captioning-lstm-rnn.git
   cd image-captioning-lstm-rnn

## Examples
2.Examples
Here are a few examples of image captioning using the models trained in this project:

**Input Image:**

Generated Caption (LSTM): "A cat sitting on a window sill."

Generated Caption (Vanilla RNN): "A cat is sitting near a window."

**Input Image:**

Generated Caption (LSTM): "A group of people standing on the beach."

Generated Caption (Vanilla RNN): "People are standing on the beach."

## Model Architecture
**LSTM Model**
The LSTM model :
is designed to capture long-term dependencies in the sequence of words generated for the image. It consists of:

An encoder that processes the input image using a pre-trained convolutional neural network (CNN) like ResNet or Inception.
A decoder that uses LSTM units to generate the sequence of words (captions).

**Vanilla RNN Model**
The Vanilla RNN model:
uses simpler RNN units without the gating mechanisms of LSTM. It includes:

A similar CNN-based encoder for image feature extraction.
A standard RNN-based decoder for caption generation.

## Dataset
The models are trained on the Flickr8k dataset, which contains a large collection of images with corresponding captions. Ensure you have downloaded and preprocessed the dataset as per the instructions in the notebook.
         https://www.kaggle.com/datasets/adityajn105/flickr8k

## Training
To train the models, run the relevant sections in the Jupyter notebook. Adjust the hyperparameters as needed:

Learning rate
Batch size
Number of epochs

## Evaluation
After training, evaluate the models using metrics like BLEU score to assess the quality of the generated captions.

## Results
Summarize the key results and compare the performance of LSTM and Vanilla RNN models based on the evaluation metrics.

  
