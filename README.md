# MIT 18.06: Linear Algebra — Prof. Gilbert Strang

This repository is based on the classic MIT 18.06 Linear Algebra course taught by Prof. Gilbert Strang. It aims to bridge the gap between mathematical theory and practical implementation using the JAX framework.

This course introduces the fundamental concepts of linear algebra and demonstrates how these concepts can be applied in code. Through interactive Jupyter notebooks and JAX-based implementations, this repository helps learners visualize and experiment with linear algebra operations.

## Topics Covered

- Vectors, linear combinations, and spans  
- Matrix multiplication and inverses  
- Gaussian elimination and LU decomposition  
- Vector spaces and subspaces  
- Orthogonality and least squares  
- Eigenvalues and eigenvectors  
- Diagonalization and symmetric matrices  
- Singular Value Decomposition (SVD)

## Code Implementation Using JAX

[JAX](https://github.com/google/jax) is a high-performance numerical computing library developed by Google. It provides NumPy-compatible syntax, GPU/TPU acceleration, and automatic differentiation. This repository uses JAX to:

- Implement matrix operations and visualizations
- Explore concepts like projections and eigen decompositions
- Reinforce understanding of linear algebra through code

## Repository Structure

```
18.06-linear-algebra-jax/
├── notebooks/                # Jupyter notebooks for each topic
│   ├── vectors_and_spaces.ipynb
│   ├── matrix_operations.ipynb
│   ├── eigenvalues.ipynb
│   └── ...
├── README.md
├── requirements.txt         # List of Python dependencies
└── LICENSE
```

## Getting Started

1. Clone the repository:

   git clone https://github.com/yourusername/18.06-linear-algebra-jax.git
   cd 18.06-linear-algebra-jax

2. Install required packages:

   pip install -r requirements.txt

3. Launch Jupyter Notebook:

   jupyter notebook

## Prerequisites

- Basic high school algebra
- Introductory Python knowledge
- Familiarity with NumPy (optional but useful)

## Acknowledgements

- [MIT 18.06 Linear Algebra Course](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/) by Prof. Gilbert Strang
- [JAX Library](https://github.com/google/jax) by Google

## License

This repository is licensed under the MIT License.
