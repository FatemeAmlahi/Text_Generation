## Auto Complete Sentences

### Dependencies

- numpy
- pandas
- matplotlib
- nltk

You can install all dependencies using:

```bash
pip install -r requirements.txt
```

### Description

This project implements a basic **n-gram language model** for natural language processing tasks, including:

- Text preprocessing and tokenization
- Vocabulary building with unknown word handling (`<unk>`)
- N-gram model construction (unigram, bigram, trigram, etc.)
- Random text generation using weighted probabilities
- Perplexity calculation with smoothing

### Evaluation

- Perplexity calculation for model evaluation
- Log-probability computation for numerical stability
- Smoothing to handle unseen n-grams

### Usage

```bash
jupyter notebook
```
