# Vision-Transformers + RoBERTa for VQA

This project demonstrates the use of Vision-Transformers (ViT) and RoBERTa models to solve the `Visual Question Answering (VQA)` task by combining image and text processing capabilities.

# Overview

In this approach, we use the following models:
- **VisionTransformer (ViT)** for processing images.
- **RoBERTa** for processing questions.

By combining the outputs from both models, we perform VQA tasks where the model predicts the answer to a question based on the provided image.

## Workflow

1. **Input**: Load an image and a question.
2. **Vision Transformer**: Extract image features using ViT.
3. **RoBERTa**: Tokenize and process the text question with RoBERTa.
4. **Combine**: Merge the outputs from both models and pass through a classifier.
5. **Output**: Generate the predicted answer for the question.

## How to Use

1. Clone the repository.
2. Open the provided `vqa_vit_roberta.ipynb` notebook file
3. Run the provided script in the notebook to install required dependencies, download and extract the dataset, and test the model on the dataset.

## Results

The approach shows promising results by combining the strengths of both ViT and RoBERTa models for Visual Question Answering tasks. The model can answer questions based on image inputs, demonstrating the potential of transformer-based models for VQA.
