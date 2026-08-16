# NumPy for Machine Learning 🧠

Jupyter notebooks documenting my journey learning NumPy — built as a foundation for machine learning.

## About

This repository contains my notes and hands-on practice while learning NumPy, the core library for numerical computing in Python. Since NumPy underlies most ML libraries (pandas, scikit-learn, PyTorch, TensorFlow), these notebooks focus on the concepts most relevant to machine learning workflows.

## Repository Structure

```
├── numpy_basics.ipynb          # Array creation, generation functions, attributes, reshaping
├── numpy_indexing.ipynb        # Indexing & slicing (vectors, matrices), boolean indexing
├── array_operations.ipynb      # Arithmetic ops, broadcasting, copies, matrix ops, stacking/splitting
├── numpy_exercises.ipynb       # Practice problems (Sudoku validator, student data analysis)
```

## Topics Covered

- [x] **Array creation** — `np.array`, `np.arange`, `np.zeros`, `np.linspace`
- [x] **Random generation** — `np.random.rand`, `randn`, `randint`
- [x] **Array attributes** — `shape`, `size`, `dtype`, `min`/`max`/`sum`/`mean`/`std`, `argmin`/`argmax`
- [x] **Reshaping** — `reshape`
- [x] **Indexing & slicing** — vectors, matrices, step slicing
- [x] **Boolean indexing** — filtering arrays with conditions
- [x] **Arithmetic operations** — element-wise `+ - * / // **`
- [x] **Broadcasting** — scalar-array operations
- [x] **Copies** — shallow (views) vs. deep (`.copy()`)
- [x] **Matrix operations** — `@`, `np.dot`, transpose (`.T`)
- [x] **Stacking & splitting** — `vstack`, `hstack`, `column_stack`, `hsplit`, `vsplit`
- [x] **Applied exercises** — Sudoku validator, filtering/aggregating tabular data

## Setup

```bash
pip install numpy jupyter
jupyter notebook
```

## Notes

This is a personal learning repo — code may be exploratory or unpolished. Feedback and suggestions are welcome!
