ASL using ANN
Overview

This project implements an Artificial Neural Network (ANN) to recognize and classify American Sign Language (ASL) gestures. The goal is to bridge communication gaps by converting hand gestures into readable text, helping to improve accessibility for individuals with hearing or speech impairments.

The model is trained on a dataset of ASL images, where each image represents a specific letter or sign. Through preprocessing and deep learning, the ANN learns to identify patterns in the images and correctly classify them into corresponding ASL symbols.

Features

Image Preprocessing: Cleans and standardizes input images (resizing, grayscale, normalization).

Feature Extraction: Converts pixel-level data into meaningful features for training.

ANN Model: Multi-layer neural network designed to capture complex gesture patterns.

Classification: Predicts the correct ASL gesture and maps it to the corresponding letter.

Extensibility: Can be scaled to handle more gestures or real-time detection with a webcam.

Dataset

The dataset contains images of ASL letters and gestures.

Images are preprocessed to ensure uniformity in size and scale.

Training and testing splits are used to evaluate model performance.

(If using a public dataset like Kaggle’s ASL dataset, include link here.)

Model Architecture

The Artificial Neural Network consists of:

Input Layer: Accepts flattened image vectors.

Hidden Layers: Multiple dense layers with activation functions (e.g., ReLU) to capture non-linear patterns.

Output Layer: Softmax activation to classify gestures into multiple categories.

Regularization techniques like dropout are used to prevent overfitting and improve generalization.

Training

Optimizer: Adam optimizer for efficient gradient updates.

Loss Function: Categorical cross-entropy to measure classification error.

Epochs: Tuned based on convergence and validation accuracy.

Evaluation: Accuracy, confusion matrix, and classification reports are generated.

Results

The ANN model achieves promising accuracy on the ASL dataset.

It successfully classifies most letters with high precision and recall.

Performance can be improved further using CNNs, data augmentation, or transfer learning.
