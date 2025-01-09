# Vision-Language Models (VLMs) with LLaVA

This project demonstrates the use of Vision-Language Models (VLMs) to solve the `Visual Question Answering (VQA)` task using the `LLaVA` model with 7 billion parameters.

# Overview

Vision-Language Models (VLMs) combine image and text processing capabilities, leveraging the advancements of Large Language Models (LLMs). By integrating visual information from a Vision Encoder with an LLM, Large Vision Language Models (LVLMs) can address tasks involving both textual and visual data, such as:
- Object Detection
- Image Captioning
- Visual Question Answering (VQA)
  
This project uses the pre-trained `LLaVA` model to answer yes/no questions based on images.

## Workflow

1. Load a test image and question.
2. Create the prompt using the question.
3. Process the image and prompt through the model.
4. Generate and display predictions.

## How to Use

1. Clone the repository.
2. Open the provided `vqa_lvlms.ipynb` notebook file
3. Run the provided script in the notebook to install required dependencies, download and extract the dataset, and test the model on the dataset.

## Results

The pre-trained LLaVA model shows strong performance on Yes/No VQA tasks without additional fine-tuning, highlighting the potential of LVLMs for real-world applications.
