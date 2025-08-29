# deutsch-joza-algorithm

This repository contains my Python implementation of the Deutsch–Jozsa Algorithm using IBM Qiskit. The algorithm is one of the foundational quantum computing examples, demonstrating an exponential speed-up over classical computation for distinguishing between constant and balanced functions.

---

## Motivation

Understand the Deutsch–Jozsa Algorithm in practice  
Learn how to build constant and balanced quantum oracles  
Apply Hadamard gates, barriers, and controlled operations in circuit design  
Simulate circuits with Qiskit Aer and interpret measurement histograms  
Create a clear reference for learning quantum algorithms  

---

## Repository Contents

### Constant & Balanced Oracles

Defines constant oracles (fixed output) and balanced oracles (equal split of 0s and 1s)  
Implemented with X and CNOT gates, with circuit visualizations  

### Deutsch Algorithm – Part 1

Prepares the two-qubit system with Hadamard and X gates  

### Deutsch Algorithm – Part 2

Applies Hadamard and measures to distinguish constant vs. balanced oracles  

### Execution & Results

Runs with either oracle using Qiskit Aer  
Outputs histograms showing deterministic results for constant oracles and 50/50 results for balanced oracles  

---

## Requirements

**Mandatory:**

```bash
pip install qiskit qiskit-aer matplotlib numpy
````

**Optional (for enhanced visualization):**

```bash
pip install qiskit-textbook
```

---

## Getting Started

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/deutsch-joza-algorithm.git
cd deutsch-joza-algorithm
```

2. **Launch Jupyter Notebook**

```bash
jupyter notebook
```

3. **Run the examples**
   Open the notebook or script, execute cells sequentially, and view:

   * Oracle circuits
   * Full Deutsch–Jozsa algorithm circuit
   * Simulation results and histograms.

---

## Reference

* **Course:** *Beginner’s Guide to Practical Quantum Computing with IBM Qiskit* (Coursera)
* **Provider:** Packt Publishing & IBM Quantum

---

## Acknowledgments

* **IBM Qiskit team** – the open-source framework
* **NumPy & Matplotlib** – math & visualization tools
---
