# Alumath-Matrix Libary
A simple matrix multiplication library as created as part of an Advanced Linear Algebra project.

# Features
1. Matrix Multiplication: Performs standard matrix multiplication with proper validation.Contains creative error messages and ASCII art animations
2. Robust Validation: Comprehensive input checking with helpful feedback
3. Lightweight: No external dependencies required

# Installation
From PyPI (Recommended)
pip install alumath-matrixlib

From Source
git clone https://github.com/Pam-Pam29/ADVANCED-LINEAR-ALGEBRA-PCA-Group-19.git
cd ADVANCED-LINEAR-ALGEBRA-PCA-Group-19
pip install .

Quick Start
from alumath_matrixlib import matrix_multiply

# Define your matrices
matrix_a = [
    [1, 2, 3],
    [4, 5, 6]
]

matrix_b = [
    [7, 8],
    [9, 10],
    [11, 12]
]

# Multiply them!
result = matrix_multiply(matrix_a, matrix_b)
print(result)
# Output: [[58, 64], [139, 154]]

## What Makes This Library Special
When everything goes right, you'll see:
✅ Matrix multiplication successful!
 /\_/\
( o.o )
 > ^ <

When things go wrong, you get helpful (and entertaining) error messages created with ASCII art!

# Technical Details
## Requirements

Python 3.6 or higher
No external dependencies

# Matrix Multiplication Rules

Matrix A (m×n) can be multiplied by Matrix B (n×p) to produce Matrix C (m×p)
The number of columns in A must equal the number of rows in B
Result matrix dimensions: rows of A × columns of B

# License
This project is licensed under the MIT License - see the LICENSE file for details.
Author
ALU Advanced Linear Algebra PCA Group 19


# Acknowledgments

Created as part of Advanced Linear Algebra coursework
Inspired by the need to make mathematical operations more engaging
Thanks to the ALU community for support and feedback

# Version History

1.0.4 - Current stable release
Includes comprehensive error handling and ASCII art animations
Supports Python 3.6+
