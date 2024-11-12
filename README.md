# Viterbi POS Tagging

This project implements the Viterbi algorithm for Part-of-Speech (POS) tagging. The objective is to decode the most probable POS tags for sentences, with a noise-handling version to account for noisy data. The steps include setting up Hidden Markov Model (HMM) parameters, implementing the Viterbi algorithm, and comparing performance with noise-handling.

## Files
- `train_data.txt`: Training data with POS-tagged sentences.
- `test_data.txt`: Test data with correct POS tags.
- `noisy_test_data.txt`: Test data with noise introduced.

## Usage
1. Run `hmm_setup.py` to set up transition and emission probabilities.
2. Run `viterbi_algorithm.py` to perform POS tagging and compare baseline and noise-handling versions.
