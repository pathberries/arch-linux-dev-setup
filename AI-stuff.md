# Setup CUDA, CUDNN, Tensorrt

https://github.com/SuperSecureHuman/Resources/blob/main/AI-ML-DL/Nvidia-Setup.md

Note that CUDA, and CUDNN are needed for any sort of GPU accelerated compute.

Tensorrt is used for optimizing the model for inference.

# Conda

Go to conda download site, and download miniconda (miniconda is stripped version of anaconda, and has lesser default packages)

Preffered python version - 3.8

# Python Packages needed

Use the pip versions of all these packages even if you have conda installed



```bash
juypter
jupyterthemes # In case you hate the blinding white of jupyter notebook
pytorch (https://pytorch.org/get-started/locally/) (Download the GPU version, pip)
tensorflow-gpu
transformers
datasets
sentence-transformers

# These packages usually have the dependencies as the regurarly used stuff
numpy, pandas, matplotlib etcc....
```

Not currently used, but may use later

```
jax
numba
cupy
pycuda
```
