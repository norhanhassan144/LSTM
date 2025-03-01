# LSTM Numerical Example Implementation

This project implements a simple LSTM cell from scratch in Python to predict the next value in a sequence.

## Overview
- The model processes a sequence `[1, 2, 3, 4]` using LSTM computations.
- The hidden and cell states are updated at each time step using sigmoid and tanh activations.
- The final hidden state is used to predict the next number in the sequence.

## Key Features
- Manual implementation of LSTM gates: forget, input, output, and candidate cell state.
- Two versions of the model:
  - **Initial version** with arbitrary weights.
  - **Optimized version** with adjusted weights to predict a value close to **4**.
