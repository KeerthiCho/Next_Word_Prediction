# Next_Word_Prediction
Next Word Prediction

## Features
- Reads a text dataset and builds a probability-based lexicon of word transitions
- Uses a Markov chain to predict the next word given the last word in a sentence
- Handles unseen words gracefully
- Uses `numpy` for weighted random selection

## Requirements
- Python 3.x
- NumPy (`pip install numpy`)
- A text dataset (`dataset.txt`) containing sample sentences

## How It Works
1. The script reads the dataset from `dataset.txt`
2. It constructs a dictionary (`lexicon`) where each word maps to possible next words with their occurrence counts
3. Counts are converted into probabilities
4. The user inputs a sentence, and the last word is used to predict the next word

## Usage
1. Prepare a text dataset named `dataset.txt` in the same directory
2. Save the script as `next_word_predictor.py`
3. Install NumPy if not already installed:
   ```bash
   pip install numpy
