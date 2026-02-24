# Financial Text Sentiment Analysis using Transformers

## Overview
This repository contains a natural language processing (NLP) project focused on performing sentiment analysis on financial texts. Implemented entirely within a Jupyter Notebook (`ML Project.ipynb`), the project leverages the power of Transformer architectures to accurately classify the sentiment (e.g., bullish, bearish, or neutral) of complex financial terminology and market-related statements.

## Architecture & Methodology
The core model is built around a custom Transformer architecture designed to understand the nuanced context of financial markets. Key components explored and implemented in this project include:
* **Word Embeddings:** To capture the semantic relationships and structural nuances of specific financial vocabulary.
* **Attention Mechanisms:** Allowing the model to dynamically focus on the most critical words and phrases within a sentence that dictate the overall market sentiment.
* **Classification Head:** A tailored output layer to predict the final sentiment probabilities.

## Project Structure
* `ML Project.ipynb`: The primary notebook containing data preprocessing steps, model construction, the training loop, and evaluation metrics.
