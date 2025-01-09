# Logarithmic Derivation Module of Hyperplane Arrangement

## Authors
Developed by **Junyan Chu** and **Shizuo Kaji**  
JC was supported by the China Scholarship Council.

---

## Overview
This module provides tools for working with the logarithmic derivation modules of hyperplane arrangements. It is implemented in [SageMath](https://www.sagemath.org/) and includes both function definitions and illustrative examples in a single Jupyter Notebook.

---

## Prerequisites
To use this module, you need to have access to SageMath. You can:
1. [Install SageMath locally](https://www.sagemath.org/download.html) on your computer.
2. Use an online service such as [CoCalc](https://cocalc.com/), which provides an environment to run SageMath.

---

## Usage Instructions
1. Open the Jupyter Notebook named **`LogarithmicVectorFieldsOfArrangements.ipynb`** in your SageMath environment.
2. Follow the instructions provided within the notebook. It contains both:
   - Function definitions for operations on hyperplane arrangements.
   - Examples demonstrating the module's functionality.

### Example
Here’s a brief example of how to use the module:

```python
A = HyperPlaneArr([[1, 0, 0], [0, 1, 0], [0, 0, 1], [1, 1, 1]])
print(gendic(A.minimal_generators))
print(A.free_resolution())
A.plot_vfield(A.minimal_generators[1], xlim=(-2, 2), ylim=(-2, 2))
```
For detailed examples and additional functionality, refer to the Examples section in the notebook.


# References

Junyan Chu, [*Free resolution of the logarithmic derivation modules of close to free arrangements*](https://arxiv.org/abs/2401.01212)


