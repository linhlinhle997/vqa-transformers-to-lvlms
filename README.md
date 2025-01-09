# CNN + LSTM for Visual Question Answering (VQA)

This project demonstrates the use of `Convolutional Neural Networks (CNN)` and `Long Short-Term Memory (LSTM)`models for solving the `Visual Question Answering (VQA)` task, where the model answers Yes/No questions based on images.

## Overview

In this project, we combine the power of `CNN` for image feature extraction and `LSTM` for processing textual data, specifically questions related to images. This hybrid approach enables the model to handle both image and text inputs effectively, providing answers to questions about the content of the images.

# Workflow

1. Load Data: The dataset contains images and corresponding questions with Yes/No answers. We load and preprocess the dataset.
2. Preprocess Text: The text (questions) is tokenized and converted into vocabulary tokens.
3. Train the Model: We use a CNN to extract features from the image and an LSTM to process the question and generate an answer.
4. Predict the Answer: The model predicts whether the answer to the question is "Yes" or "No" based on the image.

## How to Use

1. Clone the repository.
2. Open the provided `vqa_cnn_lstm.ipynb` notebook file.
3. Run the provided script to install the required dependencies, download and extract the dataset, and test the model on the dataset.

## Results

The `CNN+LSTM` model effectively answers Yes/No questions by combining image features extracted through `CNN` and sequential understanding of the question via `LSTM`, offering a strong baseline for the VQA task.