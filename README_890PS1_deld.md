# ECON 890 PS1 README

## To Run:
- I used python within JupyterLab to include Markdown Formatting
- The code is broken up into chunks:
    - Parameters and Distributions
    - Define VFI Function
    - Define Simulate VFI Function
    - Bisection Method to get Equilibrium Tax Rate
    - Results: equilibrium quantities and plots
- Despite being in chunks, the code should run as each chunk is executed from top to bottom

## Files
- '890PS1_results_deld.pdf' is a pdf writeup of questions/results
- '890PS1_code_deld.ipynb' contains all code used for the assignment

## Resources Used
- For VFI, I used Thomas Sargent and John Stachurski's guide on [QuantEcon](https://jax.quantecon.org/opt_savings_1.html)
- [Ljungqvist and Sargent (1998)](https://www.jstor.org/stable/10.1086/250020)

## Packages Required
- numpy: For VFI
- matplotlib: for creating figures
- time: For benchmarking
