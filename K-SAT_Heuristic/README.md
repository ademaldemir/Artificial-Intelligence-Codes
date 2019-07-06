# Learning Objective:

Evaluating the heuristic functions and comparison of various informed search strategies.

# Reference:

- Artificial Intelligence a Modern Approach, Russell and Norvig (third edition),
  Chapter 2, 3, 4.
- A first course in Artificial Intelligence, Deepak Khemani,
  Chapter 3, 4.

# Problem Statement:

- Write a program to randomly generate k-SAT problems. The program must accept values for k, m the number of clauses in the formula, and n the number of variables. Each clause of length k must contain distinct variables or their negation. Instances generated by this algorithm belong to fixed clause length model of SAT and are known as uniform random k-SAT problems.
- Write programs to solve a set of uniform random k-SAT problems for different combinations of m and n, and compare their performance. Try the Hill-Climbing, Beam-Search with beam widths 3 and 4, Variable-Neighborhood-Descent with 3 neighborhood functions. Use two different heuristic functions and compare them with respect to penetrance.