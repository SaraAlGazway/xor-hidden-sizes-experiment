# 🧠 XOR Classifier with Different Hidden Sizes (PyTorch)

> This notebook experiments with different hidden layer sizes to solve the XOR problem using PyTorch.

## 🎯 What this notebook covers:

- Defining the XOR dataset
- Testing multiple hidden layer sizes: [1, 2, 4, 8, 16]
- Training a neural network for each configuration
- Comparing accuracy across hidden sizes

## 📊 Expected Results:

- Small hidden sizes (1, 2) → **fail** (~50% accuracy)
- Larger hidden sizes (4, 8, 16) → **succeed** (100% accuracy)

## 🏗️ TestModel Architecture

| Layer | Type | Input | Output |
|-------|------|-------|--------|
| 1 | Linear | 2 | hidden |
| 2 | ReLU | hidden | hidden |
| 3 | Linear | hidden | 1 |
| 4 | Sigmoid | 1 | 1 |

## 🚀 How to Run

1. Open `xor-classifier-with-different-hidden-sizes-pyt.ipynb`
2. Run all cells
3. Check the results

## 📦 Requirements

```bash
pip install torch
