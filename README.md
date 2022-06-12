# cuda_collatz_lengths

This program calculates the Collatz length of random integers, and uses GPU parallel computing in CUDA.

From Wikipedia:
"The Collatz conjecture is one of the most famous unsolved problems in mathematics. The conjecture asks whether repeating two simple arithmetic operations will eventually transform every positive integer into 1. It concerns sequences of integers in which each term is obtained from the previous term as follows: if the previous term is even, the next term is one half of the previous term. If the previous term is odd, the next term is 3 times the previous term plus 1. The conjecture is that these sequences always reach 1, no matter which positive integer is chosen to start the sequence."

Consider the initial number 10, the Collatz sequence is 10→5→16→8→4→2→1, and has a sequence 6.

Code is written in CUDA, and is adapted from CUDA Vector additions tutorials found online and https://www.udemy.com/course/introduction-to-parallel-programming-using-gpgpu-and-cuda/learn/lecture/8077270#learning-tools

Notebook written for the Google Colab environment
