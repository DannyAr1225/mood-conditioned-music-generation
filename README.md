# Automatic Mood-Conditioned Symbolic Music Generation

This repository provides a portfolio summary of a Stanford CS 229 machine learning project on mood-conditioned symbolic music generation. The project explored whether deep learning models could generate MIDI-style symbolic music conditioned on emotional labels such as happy, sad, calm, and excited.

## Overview

We built a pipeline for converting MIDI files into token sequences and conditioning those sequences on emotion and genre metadata. We implemented and compared LSTM and Transformer-based architectures for symbolic music generation, then evaluated generated outputs for stylistic consistency, rhythmic structure, and musical coherence.

Full source code is not included in this repository because the project was completed as part of university coursework.

## Tech Stack

* Python
* PyTorch
* LSTM models
* Transformer models
* MIDI tokenization
* Machine learning evaluation

## Dataset

* XMIDI dataset
* 108K+ MIDI files
* 5.2K+ hours of symbolic music data

## My Contributions

* Helped build the mood-conditioned MIDI preprocessing and tokenization pipeline
* Implemented and evaluated sequence generation models using LSTM and Transformer architectures
* Analyzed model outputs for coherence, long-range structure, sparse predictions, and controllability
* Contributed to the final poster, results analysis, and discussion of model limitations

## Results

* Scaled experiments from 2K LSTM samples to 55K Transformer train/validation sequences
* Achieved 0.40 validation loss and 0.845 validation macro-AUROC with the LSTM baseline
* Found that mood-conditioned symbolic generation was feasible, while long-range musical structure and expressive controllability remained key challenges

## Note

This repository is intended as a public portfolio summary. It does not include private course code, assignment materials, datasets, or full implementation details.
