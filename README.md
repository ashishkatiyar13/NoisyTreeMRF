# Recoverability Landscape of Tree Structured Markov Random Fields under Symmetric Noise
Contains the code for the paper "Recoverability Landscape of Tree Structured Markov Random Fields under Symmetric Noise".
This repository contains 2 files:
1. k_2.ipynb
2. k_4.ipynb

The code in k_2.ipynb can be used to generate the output of our algorithm for k=2 setting.
Results for k = 4 can be generated using k_4.ipynb.

The key difference in the two files is that for k=2, we do not implement the quadratic error test as we
know a priori that no nodes within a leaf cluster can be identified.

Execution:

To execute the code, set the desired settings in the init_parameter() function. Then, execute the main() function.

