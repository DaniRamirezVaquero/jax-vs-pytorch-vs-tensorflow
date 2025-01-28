# JAX vs TensorFlow vs PyTorch: Deep Learning Framework Comparison 🥊

This repository contains a performance comparison between JAX, TensorFlow and PyTorch using a neural network classifier on the wine dataset.

## Overview

The Jupyter notebook compares:
- Implementation complexity
- Training time performance
- Model accuracy
- Framework features and ecosystem

## Key Results

- JAX achieves same accuracy as TensorFlow with 10x faster training
- All frameworks reach similar accuracy levels
- JAX requires Stax for easier model building
- Clean comparison using wine dataset from scikit-learn

## Requirements

```python
jax==0.4.13
tensorflow==2.13.0
torch==2.0.1
numpy==1.24.3
pandas==2.0.3
matplotlib==3.7.2
scikit-learn==1.3.0
seaborn==0.12.2
```

## References
- [JAX](https://github.com/google/jax)
- [Optax](https://github.com/deepmind/optax)
- [Stax](https://www.kaggle.com/code/aakashnain/building-models-in-jax-part1-stax)

## Author
[Daniel Ramírez Vaquero](https://github.com/DaniRamirezVaquero)