# Named Entity Recognition (NER) in Arabic

This project demonstrates three different approaches for performing Named Entity Recognition (NER) on Arabic text: using spaCy, a Bi-LSTM model, and AraBERT.

## Approaches
### 1. NER with spaCy
 - Utilizes spaCy, an open-source library for advanced NLP, to perform NER on Arabic text. Pre-trained models in spaCy are adapted for Arabic entity recognition tasks.
### 2. NER with Bi-LSTM
 - A Bidirectional Long Short-Term Memory (Bi-LSTM) model is trained for NER, using a sequence-based approach to label words in a sentence as named entities (e.g., persons, locations, organizations).
 - The model captures both past and future context in the sentence to improve accuracy.
### 3. NER with AraBERT
 - AraBERT, a pre-trained transformer model, is fine-tuned on Arabic NER data. This approach leverages the power of transformer architectures for more accurate entity recognition.

## Dataset
All three approaches use an Arabic NER dataset, which contains labeled sentences with entities such as persons, locations, and organizations.

## Workflow

Each approach is implemented in a separate notebook:
1. spaCy NER: A rule-based and statistical model is used to detect and classify named entities.
2. Bi-LSTM NER: The Bi-LSTM model is trained from scratch on the NER dataset using word embeddings and character-level features.
3. AraBERT NER: AraBERT is fine-tuned on the same dataset to perform entity classification.

## Usage
Clone the repository and run each notebook individually to explore the different NER approaches. Each notebook is self-contained, and the corresponding model for each approach can be used to perform NER on Arabic text.
