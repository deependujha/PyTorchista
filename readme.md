# PyTorch 🐍🔦

## What is PyTorch?

PyTorch is an open-source machine learning library for Python, developed primarily by Facebook's AI Research (FAIR) lab. **It provides a framework for building and training neural networks, including deep learning models**.

> It’s a Python-based scientific computing package targeted at two sets of audiences:
> - A replacement for NumPy to use the power of GPUs
> - a deep learning research platform that provides maximum flexibility and speed

---

## Using MPS on Mac

```python
import torch

if torch.backends.mps.is_available():
    mps_device = torch.device("mps")
    x = torch.ones(1, device=mps_device)
    print (x)
else:
    print ("MPS device not found.")
```

---

## Contents 🛂

1. [Tensors & Operations](./01_tensors_and_operations/)