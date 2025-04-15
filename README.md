# NDLinearExperiment

This repository contains experiments that compare the performance of traditional PyTorch linear layers (`nn.Linear`) with **NdLinear**—a next-generation, multi-dimensional linear transformation module. In these experiments, we explore the use of NdLinear in two settings:

1. **CNN for Image Classification**: Applying NdLinear in a convolutional neural network using the EMNIST "digits" dataset.
2. **Transformer for Text Classification**: Replacing standard feed-forward layers with NdLinear in a Transformer encoder for classifying AG News articles.

The experiments compare models based on training time, accuracy, and efficiency. Visual graphs are provided to illustrate the differences.

## Features

- **NdLinear Module**: Preserves the multi-dimensional structure of data while reducing parameter count and maintaining efficiency.
- **CNN Experiment**: Demonstrates integration of NdLinear in a CNN on the EMNIST dataset.
- **Transformer Experiment**: Shows how to replace standard linear layers with NdLinear within a custom Transformer encoder using the AG News dataset.
- **Performance Metrics**: Compares training time and test accuracy with graphical visualizations.
- **Hugging Face Integration**: Utilizes Hugging Face's `datasets` and `transformers` for tokenization and dataset loading.
- **Google Colab Ready**: The experiments are designed to be run in Google Colab.
