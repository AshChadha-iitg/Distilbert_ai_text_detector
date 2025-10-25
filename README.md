# DistilBERT AI Text Detector
This is a binary text classification model built on top of **distilbert-base-uncased**. It has been fine-tuned to distinguish between AI-generated and human-written text.


# Base model: 
DistilBERT (uncased)


# Task: Sequence classification

**Labels:**

0 → Human-written text

1 → AI-generated text


# Training Details:

Model is fine-tuned on a small custom dataset of **~1.4k samples**

**Batch size: 16**

**Epochs: 10**

**Learning rate: 5e-6**


# Performance:

**Accuracy: 0.5693 (~57%)**

**Precision: 0.6162**

**Recall: 0.9858**

**F1-score: 0.6814**


# Usage

Load the model and tokenizer with the Hugging Face Transformers library, provide a text input and the model will output a label indicating whether the text is AI-generated or human-written.


# Framework:

PyTorch, Hugging Face Transformers


# License: MIT License


# NOTE: 
This model is experimental and not intended for production use
