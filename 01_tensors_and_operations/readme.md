# Tensors 👑

## What is a Tensor?

A tensor is a generalization of vectors and matrices and is easily understood as a multidimensional array.

- A vector is a one-dimensional or first order tensor and a matrix is a two-dimensional or second order tensor.

> Tensors in PyTorch are similar to NumPy arrays, but with some important differences. 

- First, **tensors can be easily moved to a GPU for fast parallel computation, which is critical for deep learning models that require large amounts of computation**. 

- Second, **PyTorch tensors automatically track the computational graph of operations that are performed on them, which enables efficient backpropagation for computing gradients during training**.

<br/>

> ### `Tensors` in PyTorch can be created using the 'torch.Tensor' class.

- Or, one of the many convenience functions provided by the PyTorch library, such as `torch.zeros`, `torch.ones`, or `torch.rand`. 

<br/>

- `Tensors can be indexed and sliced in the same way as NumPy arrays`.

- **PyTorch provides many functions** for performing mathematical operations on tensors, such as `element-wise addition` and `multiplication`, `matrix multiplication`, and more advanced operations like `convolutions` and `pooling`.

