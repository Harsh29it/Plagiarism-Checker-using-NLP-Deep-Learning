# Plagiarism Checker using NLP & Deep Learning

## Overview
This project is an NLP-based plagiarism detection system that uses Deep Learning techniques to identify similarity between two text documents.  
A Siamese LSTM Neural Network is used to compare sentence pairs and predict whether the text is plagiarized or not.

---

## Features
- Text preprocessing and cleaning
- Tokenization and sequence padding
- Siamese LSTM architecture
- Similarity-based plagiarism detection
- Model training and evaluation using TensorFlow/Keras

---

## Tech Stack
- Python
- TensorFlow / Keras
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Seaborn

---

## Dataset
The model is trained on sentence-pair text data containing:
- Source text
- Compared text
- Label (Plagiarized / Not Plagiarized)

---

## Workflow
1. Load and preprocess dataset
2. Clean and normalize text
3. Convert text into sequences
4. Train Siamese LSTM model
5. Compare text similarity
6. Predict plagiarism probability

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/plagiarism-checker-nlp.git
