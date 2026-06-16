# LSTM Next Word Prediction using TensorFlow

## Overview

This project implements a **Next Word Prediction Model** using **LSTM (Long Short-Term Memory)** networks in TensorFlow/Keras. The model is trained on a text corpus and learns sequential patterns to predict the most likely next word given an input sequence.

## Features

- Text preprocessing and tokenization
- Sequence generation for language modeling
- Sequence padding
- LSTM-based neural network
- Next-word prediction
- TensorFlow/Keras implementation

## Tech Stack

- Python
- TensorFlow
- Keras
- NumPy
- Google Colab

## Model Architecture

```text
Embedding Layer (100 Dimensions)
        ↓
LSTM Layer (150 Units)
        ↓
Dense Layer (Softmax Activation)
```

### Model Configuration

| Parameter | Value |
|------------|--------|
| Vocabulary Size | 283 |
| Embedding Dimension | 100 |
| LSTM Units | 150 |
| Activation Function | Softmax |
| Optimizer | Adam |
| Loss Function | Categorical Crossentropy |

## Workflow

1. Load and preprocess the text corpus.
2. Tokenize the text using Keras Tokenizer.
3. Create input sequences.
4. Pad sequences to a fixed length.
5. Train an LSTM model on the prepared data.
6. Predict the next word for a given input sequence.
7. Generate multiple words iteratively.

## Example

### Input

```text
nlp and deep learning
```

### Generated Output
