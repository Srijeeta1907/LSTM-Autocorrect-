# LSTM Next-Word Predictor (Autocorrect)
A Natural Language Processing model that uses Recurrent Neural Networks to predict the most statistically probable next word in a sentence.

## Overview
This project simulates the core technology behind smartphone autocorrect features. It utilizes an LSTM (Long Short-Term Memory) network to retain the context of preceding N-gram sequences, allowing it to accurately anticipate user input.

## Tech Stack
* **Framework:** TensorFlow / Keras
* **Language:** Python
* **Data Processing:** Keras Tokenizer, pad_sequences, NumPy

## How it Works
1. Ingests raw text and converts words into numeric tokens.
2. Generates and pads N-gram sequences to create a consistent training matrix.
3. Utilizes an Embedding layer and an LSTM layer to learn the contextual relationships between word sequences before outputting categorical probabilities.
