Named Entity Recognition (NER) with Hugging Face Transformers 🚀

This project demonstrates how to build and train a Named Entity Recognition (NER) model using the Hugging Face Transformers library in Python. The model is based on a pre-trained transformer (distilbert-base-cased) and fine-tuned for entity recognition tasks such as identifying names, locations, organizations, and other entities.

📌 Features

Uses DistilBERT (distilbert-base-cased) as the base model

Fine-tunes on the CoNLL-2003 dataset

Supports standard NER labels like O, B-MISC, I-MISC, B-ORG, I-ORG, B-PER, I-PER, B-LOC, I-LOC

Configurable label mappings for training & evaluation

Dataset loading from a ZIP file with preprocessing

Trained model automatically saved to Google Drive (Colab integration)
