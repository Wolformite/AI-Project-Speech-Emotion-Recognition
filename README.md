# AI-Project-Speech-Emotion-Recognition
Project for speech emotion recognition using CNNs

Speech Emotion Recognition using CNN
This project implements a **Speech Emotion Recognition** (SER system using a **2D Convolutional Neural Network** (CNN) trained on the RAVDESS dataset.

The model converts speech audio into **Log-Mel Spectrograms** and classifies emotions into 8 categories.

---

## Project Overview

The goal of this project is to combine **Digital Signal Processing** and **Deep Learning** to identify emotions from human speech.

Audio signals are transformed into image-like representations (Log-Mel Spectrograms), which are then processed by a CNN model.

---

## Target Emotions

- Neutral  
- Calm  
- Happy  
- Sad  
- Angry  
- Fearful  
- Disgust  
- Surprised  

---

## Model Architecture

The model is a **2D Convolutional Neural Network** consisting of:

- Conv2D Layers
- Batch Normalization
- MaxPooling
- Global Average Pooling
- Dropout Regularization
- Dense Softmax Output

---

## Dataset

RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song)

Expected folder structure:
