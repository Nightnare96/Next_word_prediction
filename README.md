# Next Word Prediction using LSTM

## Project Overview

This project implements a **Next Word Prediction model** using Natural Language Processing and Deep Learning. The model is trained on text from *The Adventures of Sherlock Holmes* by Arthur Conan Doyle, taken from Project Gutenberg. The objective is to predict the next word based on a given sequence of words.

The project uses tokenization, sequence generation, padding, and an LSTM-based neural network to learn language patterns from the text and generate the next predicted words.

## Dataset

The dataset contains text from:

**The Adventures of Sherlock Holmes**  
Author: Arthur Conan Doyle  
Source: Project Gutenberg eBook

The text is used to train the language model for next-word prediction. :contentReference[oaicite:0]{index=0}

## Features

- Text preprocessing
- Tokenization using Keras Tokenizer
- Sequence generation for language modeling
- Padding of input sequences
- LSTM-based deep learning model
- Next word prediction
- Multi-word text generation

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Natural Language Processing
- Google Colab

## Model Workflow

1. Load the text dataset
2. Clean and preprocess the text
3. Convert words into numerical tokens
4. Create input-output sequences
5. Pad sequences to equal length
6. Train an LSTM model
7. Predict the next word
8. Generate multiple words step-by-step

## How to Run

1. Open the notebook in Google Colab
2. Install required libraries if needed
3. Run all cells step by step
4. Enter a seed word or phrase
5. The model will predict the next words

## Example

Input:

```python
test = "eBook"# Next_word_prediction
```


Output:
```python
eBook is
eBook is for
eBook is for the
eBook is for the use

