# LSTM Implementation From Scratch

This repository contains a pure Python implementation of a **Long Short-Term Memory (LSTM)** network. The project focuses on demonstrating the internal mechanics of LSTM gates through a detailed numerical example, built entirely without deep learning frameworks like TensorFlow or PyTorch.

## 📌 Project Overview
The goal of this implementation is to provide a clear, step-by-step understanding of how data flows through an LSTM cell. It follows the standard mathematical formulas for:
*   **Forget Gate** ($f_t$)
*   **Input Gate** ($i_t$)
*   **Candidate Cell State** ($\tilde{C}_t$)
*   **Cell State Update** ($C_t$)
*   **Output Gate** ($o_t$)
*   **Hidden State Update** ($h_t$)

## 🧮 Numerical Example
The code processes a sequence $[1, 2, 3]$ to predict the next value. It uses predefined weights and biases to ensure the results can be manually verified against theoretical calculations.

### Key Features:
- **Zero Dependencies:** Uses only `NumPy` for mathematical operations.
- **Detailed Logs:** Prints every intermediate gate value for each time step.
- **Object-Oriented:** Structured using a class-based approach for better readability.

## 🚀 How to Run
1. Clone the repository.
2. Ensure you have `numpy` installed: `pip install numpy`.
3. Run the notebook or the script to see the step-by-step calculations.

## 📊 Sample Output
The model successfully learns the pattern and predicts the next value in the sequence with high precision, matching expected theoretical results.
