# ECGR4106 - Homework 4

## Student Information

**Name:** Samantha Gonzalez  
**Student ID:** 801353957

**Course:** ECGR 4106 - Introduction to Deep Learning  
**Assignment:** Homework 4

---

## Repository Contents

This repository contains all source code and results for Homework 4.

### Files

- `train.py` - Main training and evaluation code for all four problems.
- `ECGR4106_Homework4.ipynb` - Google Colab notebook with all code executed and outputs visible.
- `results/` - CSV files, graphs, and comparison figures generated during training.

---

## Homework Overview

### Problem 1
Transformer model for character-level next character prediction.

The transformer was trained using sequence lengths of:
- 10
- 20
- 30

The results were compared with the RNN, LSTM, and GRU models from Homework 2.

Reported metrics include:
- Training loss
- Validation accuracy
- Training time
- Model size
- Computational complexity

---

### Problem 2
Transformer model for the Tiny Shakespeare dataset.

Experiments include:
- Sequence lengths of 20 and 30
- Sequence length of 50
- Different numbers of transformer blocks
- Different numbers of attention heads

Reported metrics include:
- Training loss
- Validation accuracy
- Training time
- Model complexity
- Model size
- Perplexity

---

### Problem 3
Transformer encoder-decoder model for English-to-French machine translation.

Reported metrics include:
- Training loss
- Validation loss
- Sequence accuracy
- BLEU-4 score
- Sample translations

The transformer results are also compared with the GRU models from Homework 3.

---

### Problem 4
Transformer encoder-decoder model for French-to-English machine translation.

Reported metrics include:
- Training loss
- Validation loss
- Sequence accuracy
- BLEU-4 score
- Sample translations

The final section compares both translation directions and previous Homework 3 results.

---

## Results

All generated figures and CSV files are located in the `results` folder.

These include:
- Training loss plots
- Validation accuracy plots
- BLEU score comparisons
- Model size comparisons
- Training time comparisons
- Hyperparameter comparisons
- Sample translations
- Summary CSV files

---

## Software

This project was developed and tested using:

- Python 3
- Google Colab
- PyTorch
- NumPy
- Pandas
- Matplotlib
- NLTK

---

## GitHub Repository

This repository contains all source code, generated results, and the executed notebook required for Homework 4.
