# Quantum-Computing-3SAT

In this repository, we can find the files used in the bachelor's thesis 'Solving the 3-SAT problem using quantum algorithms' done by Arnau Casau at FIB - UPC Universitat Politècnica de Catalunya.

Quantum computing is a new and emerging field, and in this thesis, we will see how to solve the 3-SAT problem using quantum algorithms.

The first approach to the problem can be found in the notebook Part-1-3SAT-Quantum-Computing.ipynb, in which we will use Grover's algorithm with a given formula to find its possible solutions. Grover's algorithm allows us to achieve a quadratic speedup over a brute-force search in all the possible assignments of the variables in the formula. At the same time, we will use the Quantum counting algorithm to determine how many solutions there are beforehand to maximize the probability of success in Grover's by repeating the Grover operator a certain number of times. In the text file cnf_test1.txt, we can see the formula the notebook uses as input.

The second part of the thesis explores how classical computers can solve the problem better than Grover's algorithm and what we can do about it. We will focus on Schöning's random walk algorithm, one of the best classical algorithms for 3-SAT. 

In the second notebook, Part-2-3SAT-Grover-Schoning.ipynb, we find an implementation of Schöning's algorithm as the oracle of Grover's algorithm (generalized as Amplitude Amplification). Combining the two algorithms, we achieve a quadratic speedup over Schöning's classical algorithm. In the text file cnf_test2.txt, we can see the formula the notebook uses as input.

To implement all the algorithms, we will use Python and Qiskit, an open-source software development kit (SDK) developed by IBM to work with quantum computers.
