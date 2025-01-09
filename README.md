# Visual Question Answering (VQA) with Transformer-Based Models

This project demonstrates various approaches for solving the `Visual Question Answering (VQA)` task using different combinations of image and text processing models. The goal is to answer questions about images using advanced deep learning models, specifically leveraging the power of `CNN`, `LSTM`, `Vision Transformers (ViT)`, `RoBERTa`, and `LLaVA` for improved performance.

## Overview

This repository includes three distinct approaches for tackling the VQA task:

1. **CNN + LSTM**: Combines `Convolutional Neural Networks (CNN)` for image feature extraction and `Long Short-Term Memory (LSTM)` for processing textual data (questions). This hybrid approach is aimed at answering Yes/No questions based on image content.

2. **Vision-Transformers (ViT) + RoBERTa**: Uses `Vision Transformer (ViT)` for image feature extraction and `RoBERTa` for processing questions. By combining the outputs from both models, this approach predicts answers to questions based on the image.

3. **Vision-Language Models (VLMs) with LLaVA**: Utilizes the `LLaVA` model, a pre-trained Vision-Language Model, for answering Yes/No questions about images. This model integrates visual information from a Vision Encoder with a Large Language Model (LLM) for enhanced performance on VQA tasks.

## Workflow

For each approach, the general workflow is as follows:
1. Load and preprocess the dataset containing images and questions.
2. Process the image and question using the respective model (CNN+LSTM, ViT+RoBERTa, or LLaVA).
3. Predict the answer to the question based on the image.

## How to Use

1. Clone the repository.
2. Open the appropriate notebook file for the desired approach:
   - `vqa_cnn_lstm.ipynb` for the CNN + LSTM approach.
   - `vqa_vit_roberta.ipynb` for the ViT + RoBERTa approach.
   - `vqa_lvlms.ipynb` for the LLaVA approach.
3. Run the provided script in the notebook to install required dependencies, download the dataset, and test the model.

## Results

Each approach provides insights into the potential of different models for VQA tasks:
- The **CNN + LSTM** model serves as a strong baseline for answering Yes/No questions.
- The **ViT + RoBERTa** approach demonstrates the power of transformer-based models in combining vision and language understanding.
- The **LLaVA** model highlights the power of large vision-language models in performing VQA tasks with minimal fine-tuning.

These models showcase the strength of transformer-based architectures for VQA, improving performance and providing a strong foundation for future applications in vision-language tasks.

