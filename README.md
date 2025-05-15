# Cyber Threat Detection Model

An NLP model based on DistilBERT for detecting cyber threats in text data through token classification.

## Project Overview

This model is an AI solution that analyzes cybersecurity texts to identify potential threats. Trained using the DistilBERT architecture, it can detect sections containing threat elements in cybersecurity-related texts.

## Features

- Automatic detection of cyber threat sections in text
- DistilBERT-based token classification architecture
- Classification of threat-related categories (diagnosis)
- High accuracy and low false positive rate

## Dataset

The model is trained on a specialized dataset consisting of cybersecurity texts, including:

- Cyber attack reports
- Security vulnerability notifications
- Threat intelligence documents
- Vulnerability analyses

## Model Architecture

The project is based on the DistilBERT model from Hugging Face's Transformers library. The model architecture consists of:

- **Base Model**: DistilBERT (distilbert-base-uncased)
- **Output Layer**: Token classification layer
- **Training Parameters**:
  - Batch Size: 16
  - Epochs: 3
  - Weight Decay: 0.01
