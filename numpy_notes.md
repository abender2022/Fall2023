# NumPy and Matplotlib Basics

This README provides an overview of some fundamental functions in NumPy (Numerical Python) and Matplotlib, two popular libraries for numerical computing and data visualization in Python.

## NumPy

### np.zeros

`np.zeros` is a NumPy function used to create an array filled with zeros. It takes the shape of the desired array as its argument and returns a new array of the specified shape, with all elements initialized to 0.

```python
import numpy as np

# Create a 2x3 array filled with zeros
zeros_array = np.zeros((2, 3))
print(zeros_array)
```

```
# Create a 4x4 identity matrix
identity_matrix = np.eye(4)
print(identity_matrix)
```
