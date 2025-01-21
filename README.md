# Transformer from Scratch

An implementation of the Transformer architecture for Neural Machine Translation (NMT) in PyTorch, based on the "Attention is All You Need" paper.

## Project Structure

- [config.py](config.py) - Configuration settings for the model and training
- [model.py](model.py) - Core Transformer model implementation
- [dataset.py](dataset.py) - Dataset handling and processing
- [train.py](train.py) - Training loop and validation
- [translate.py](translate.py) - Inference script for translations
- [train_and_inference.ipynb](train_and_inference.ipynb) - Jupyter notebook for interactive training and testing

## Features

- Full Transformer architecture implementation
- Multi-head attention mechanism
- Positional encoding
- Layer normalization
- Residual connections
- TensorBoard integration for training visualization

## Setup & Training

1. Install requirements:
```bash
pip install torch datasets tokenizers torchmetrics tensorboard tqdm