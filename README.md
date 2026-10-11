# Algebraic_Computing_System (CLI)

---

[![Python Version](https://img.shields.io/badge/python-3.8%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

> A robust, command-line Computer Algebra System (CAS) built in Python. This tool bridges symbolic mathematics, numerical computation, and publication-quality data visualization to solve, analyze, and graph college-level algebraic expressions.

---

## Key Features

* **Basic Arithmetic & Proportions:** Perform standard operations and solve cross-multiplications with or without unknown variables.
* **Indices & Radicals:** Simplify exponent expressions and radical terms, complete with dedicated graphing modules.
* **Polynomial Engine:** Handle polynomials of any degree:
  * Solve equations for real roots.
  * Factor and expand algebraic expressions.
  * Simplify complex forms.
  * Generate high-resolution plots highlighting roots, critical points, and axes of symmetry.
* **Inequality Solver & Plotter:** Compute univariate inequality solution sets and visualize solution regions using shaded Matplotlib plots.

---

## Tech Stack

* **Language:** Python 3.10
* **Symbolic Engine:** [SymPy](https://www.sympy.org/) (Algebraic manipulation, solving, factoring)
* **Numerical Computing:** [NumPy](https://numpy.org/) (Data processing, array operations)
* **Visualization:** [Matplotlib](https://matplotlib.org/) (Plotting roots, symmetry axes, and inequality regions)
* **Environment:** Conda

---

## Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Shamas1941/Algebraic-Computing-System-CLI.git
   cd Algebraic-Computing-System-CLI```

2. Create and activate the Conda environment:
   ```bash
   conda env create -f environment.yml
   conda activate algebraic-env```

3. Run the program:
   ```bash
   python main.py```