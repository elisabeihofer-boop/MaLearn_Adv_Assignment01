# Mutlilingual Tokenization and Language Modeling

## Part 1: The Tokenizers

- `tokenizers.ipynb`
- `artifacts/tokenizers/`

Trained a character-level tokenizer, a 3k vocabulary BPE tokenizer, and a 10k vocabulary BPE tokenizer with shared vocabulary on English, Turkish, and Chinese data from: Leipzig Corpora Collection, Wikipedia sentence corpora, 2021, 100K

## Part 2: The Language Models

- `language_models.ipynb`
- `artifacts/models/`

Trained three different decoder-only Transformer language models from scratch, one for each tokenization condition

## Part 3: Evaluation and Analysis

- `evaluation.ipynb`

Evaluated each model separately on English, Turkish, and Chinese + investigated vocabulary allocation and how tokenization relates to model behavior



My report contains more detailed information on how this experiment was conducted and its results.
