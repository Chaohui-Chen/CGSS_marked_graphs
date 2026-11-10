# Computational Verification

**Paper:** *A Cameron–Goethals–Seidel–Shult theorem for marked graphs*

**Authors:** Chaohui Chen, Muhuo Liu, Haiying Shan, and Zoran Stanić.

This repository contains the SageMath code for the computations in Section 6 of the accompanying paper.

## Files

- `CGSS_marked_graphs.ipynb`: SageMath notebook containing the verification code and computational results.

## Requirements

SageMath 10.7 or later.

## Usage

Open `CGSS_marked_graphs.ipynb` in Jupyter Notebook using the SageMath kernel and run all cells.

To launch Jupyter Notebook from SageMath, use:

```bash
sage -n jupyter
```

## Expected Results

Among connected graphs of order 8:

- 2182 have second largest eigenvalue at most 1.
- 1731 of these have complements with smallest eigenvalue at least −2.
- 2132 are −2-markable.

These results correspond to the computations presented in Section 6 of the paper.
