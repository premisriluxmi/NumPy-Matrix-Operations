# NumPy Matrix Operations

A beginner-level Python project demonstrating basic matrix operations using NumPy.

## Objective

To create two NumPy matrices and perform:

- Matrix addition
- Matrix subtraction
- Matrix multiplication
- Matrix transpose

## Technologies Used

- Python 3
- NumPy
- Jupyter Notebook

## Python Functions and Concepts Used

- `np.array()` – to create matrices
- `+` – to perform matrix addition
- `-` – to perform matrix subtraction
- `@` – to perform matrix multiplication
- `.T` – to transpose a matrix
- `.shape` – to check matrix dimensions

## Results

| Operation | Result |
|---|---|
| Addition | `[[6, 8], [10, 12]]` |
| Subtraction | `[[-4, -4], [-4, -4]]` |
| Matrix Multiplication | `[[19, 22], [43, 50]]` |
| Transpose of Matrix 1 | `[[1, 3], [2, 4]]` |
| Transpose of Matrix 2 | `[[5, 7], [6, 8]]` |
| Shape of Both Matrices | `(2, 2)` |

## Explanation

Two matrices were created using NumPy's `np.array()` function.

Addition and subtraction were performed on corresponding elements.

Matrix multiplication was performed using the `@` operator. It multiplies rows of the first matrix by columns of the second matrix.

The transpose operation using `.T` converts rows into columns.

These operations demonstrate basic matrix calculations used in numerical computing and machine learning.

## How to Run

1. Open `NumPy_Matrix_Operations.ipynb` in VS Code or Jupyter Notebook.
2. Ensure NumPy is installed. If needed, run `pip install numpy` in the terminal.
3. Select the Python kernel.
4. Run all notebook cells from top to bottom.
5. View the matrix operation results.

## Learning Outcome

- Learned how to create NumPy matrices.
- Practiced matrix addition and subtraction.
- Understood the basics of matrix multiplication.
- Learned how to transpose matrices.
- Gained experience with matrix operations used in machine learning.

## Project Structure

```text
NumPy-Matrix-Operations/
│
├── NumPy_Matrix_Operations.ipynb
└── README.md
```