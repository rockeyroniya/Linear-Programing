# Introduction to Linear Programming with Python

Linear Programming (LP), also known as linear optimization, is a powerful mathematical technique used to maximize or minimize a linear objective function subject to a set of linear equality and inequality constraints.

LP has widespread applications, especially in operations management, but it can solve a diverse range of problems including:

- **Scheduling** — Designing optimal employee rotas or factory schedules  
- **Resourcing Problems** — Allocating limited resources to maximize profits or efficiency  
- **Blending Problems** — Cost-effective mixing of components to meet quality and quantity needs  
- **Puzzle Solving** — Examples like Sudoku  

Leonard Kantorovich was awarded the Nobel Prize in Economics in 1975 for pioneering work on optimal resource allocation using linear programming.

---

This repository contains the theory and practical application of linear programming using Python.

We utilize the [PuLP](https://coin-or.github.io/pulp/) package, which provides a Pythonic interface for defining and solving LP problems. PuLP includes the CBC solver and integrates with commercial solvers such as Gurobi and CPLEX.

---

## Included Notebooks and Files (in order)

1. **Introduction to Linear Programming.ipynb**  
   Overview of LP concepts and fundamentals, including mathematical background and simple examples.

2. **How to Formulate a Linear Programming Problem.ipynb**  
   Guides you through translating real-world scenarios into LP models, with emphasis on defining objectives and constraints.

3. **Solving LP in Python Using PuLP.ipynb**  
   Practical walkthrough on using PuLP to define and solve LP problems with code examples.

4. **Solving Linear Programming Using Gurobi.ipynb**  
   Demonstrates how to use the commercial Gurobi solver for enhanced performance and larger-scale problems.

5. **A Diet Planning Problem using Linear Programming.ipynb**  
   An applied example of diet optimization using LP, focusing on nutrition and cost constraints.

6. **Factory Production Planning.ipynb**  
   Detailed example of production scheduling and resource allocation in a factory environment.

7. **Linear Programming in Practice-Maximizing Factory Profit.ipynb**  
   Real-world factory profit maximization example, with multiple constraints including resource limits, demand, and setup costs.

8. **Scheduling Employees for Shifts.ipynb**  
   Employee scheduling problem using LP to meet shift demands while respecting employee constraints.



## Installation

Make sure you have Python installed (version 3.6 or above recommended).

Install required packages using pip:

```bash
pip install pulp
