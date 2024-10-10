# Machine_Translation
**Overview**

This repository contains a machine translation model built from scratch using the Transformer architecture. The project focuses on translating text from English to Italian. By implementing the Transformer model from scratch, this project demonstrates key concepts like self-attention, multi-head attention, and positional encoding.The model has been designed to handle sequence-to-sequence translation tasks efficiently by leveraging transformers without relying on pre-trained models.

**Features**

*Transformer-based sequence-to-sequence architecture.

*Scalable to various language pairs (e.g., English to French, German to English).

*Full implementation of the Transformer model, including:

*Multi-head self-attention

*Positional encoding

*Encoder-decoder structure

*Layer normalization and residual connections

*Support for tokenization, padding, and sentence numericalization.

*Efficient use of GPUs (e.g., tested on Tesla T4 with CUDA for fast training).

*Evaluation using BLEU scores and translation quality metrics.


**Requirements** 

*Python 3.8+

*PyTorch 2.0+

*Torchtext

*Torchmetrics

*Numpy

*tqdm

*Jupyter Notebook (for running experiments)
