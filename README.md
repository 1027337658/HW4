# Bayesian Homework: MH within Gibbs, Updated MH, and Discrete MH Transition Kernel

This repository contains my solution to a Bayesian homework assignment. The notebook presents implementations and discussions for the following tasks:

- **Q1:** Conversion of the full conditional Gibbs sampler from HW3-Q2 into a Metropolis‐within‐Gibbs (MH within Gibbs) sampler. This section includes a qualitative comparison of the inference provided by the MH approach versus the original Gibbs sampler.
- **Q2:** An updated MH within Gibbs sampler that employs a dependent proposal for \(\tau\) (using a truncated normal distribution) and a non‐normal (Laplace) prior for \(\theta\). In this section, I also discuss the necessity (or lack thereof) of deriving analytical full conditional distributions when using MH updates.
- **Q3:** A demonstration of the discrete Metropolis–Hastings algorithm by simulating a two-state chain. The notebook shows how the transition kernel \(K\) is produced and verifies that the empirical transition probabilities match the theoretical expectations.

All results, plots, and explanations are contained in a well-documented Jupyter Notebook with clear markdown cells that detail my reasoning and the implementation steps.

---

## File Structure

- `homework.ipynb`  
  The main notebook file containing all code, explanations, and visualizations for the assignment.

- `README.md`  
  This file, which provides an overview and instructions for the repository.

---

## Requirements

The notebook uses the following Python libraries:

- **Python 3**
- **numpy**
- **matplotlib**
- **scipy**
- **plotly**

---


## Author
- **Name:** [Yuanting Han]
- **Email:** [q2900725257@gmail.com]
  
