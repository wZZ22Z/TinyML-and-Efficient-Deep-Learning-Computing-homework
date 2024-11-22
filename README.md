# TinyML and Efficient Deep Learning Computing Homework

This project is a coursework submission for the **TinyML and Efficient Deep Learning Computing** course, completed using **Google Colab** for implementation. The project explores key topics in TinyML through a series of focused labs.

## Project Overview

The project is divided into four labs, each addressing a critical aspect of TinyML and efficient deep learning:

- **Lab 1**: Focus on **Pruning** – Reducing model size by removing unnecessary parameters while maintaining performance.
- **Lab 2**: Focus on **Quantization** – Applying techniques to reduce model precision for efficient inference.
- **Lab 3**: Focus on **Neural Architecture Search (NAS)** – Automatically discovering optimal model architectures.
- **Lab 4**: Focus on **Quantization of Large Language Models (LLMs)** – Adapting quantization techniques for LLMs to improve efficiency.

## Google Colab for code execution and experimentation.

## Lab 4
#### Computation Intensity = \frac{\text{FLOP}}{\text{Byte}}. 
- High computation intensity means computation bound, low computation intensity implies memory bound.
#### GEMV( General Matrix-Vector Multiplication), #FLOP = 2mn
#### wikitext-2
- Extracted from high-quality Wikipedia articles, cleaned and curated
- generally used for language models
#### Perplexity
- Perplexity is a performace metric representing the level of uncertainty or confusion a model has when predicting the next word in a sequence.
- Low perplexity: Indicates that the model is confident and assigns higher probabilities to the correct next word.
- High perplexity: Indicates that the model has low confidence and assigns lower probabilities to the correct next word.
- examples: If perplexity = 10, the model will choose from 10 possible candidates for the next word.


