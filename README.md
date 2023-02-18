# Quantum-Computing-3SAT

In this repository, we can find the files used in the bachelor's thesis Solving the 3-SAT problem using quantum algorithms done by Arnau Casau at FIB - UPC Universitat Politècnica de Catalunya.

The notebook *Part-1-3SAT-Quantum-Computing.ipynb* contains the implementation of Grover's algorithm using Qiskit. In this notebook, we can also find the code of the Quantum counting algorithm used to determine the number of iterations we need at Grover's and some explanations of the process. In the txt file  *cnf_test1.txt*, we can see the formula that the notebook uses as input.

In the second notebook, *Part-2-3SAT-Grover-Schoning.ipynb*, we can find an implementation of Schöning's algorithm (Classical random walk algorithm to solve 3-SAT better than Grover's quantum algorithm) as the oracle of Grover's algorithm. Combining the two algorithms, we achieve a quadratic speedup over Scöning's classical algorithm. In the txt file *cnf_test2.txt*, we can see the formula that the notebook uses as input.
