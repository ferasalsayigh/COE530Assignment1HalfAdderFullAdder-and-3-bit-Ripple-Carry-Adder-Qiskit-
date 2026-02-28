# COE530 – Quantum Computing Assignment 1  
**Feras Alsayigh**  
Under the supervision of **Dr. Muhamad Felemban**

---

## Overview

This assignment implements classical arithmetic circuits using **reversible quantum logic** in IBM Qiskit. The following circuits were designed, analyzed, and executed:

- Half Adder (HA)
- Full Adder (FA)
- 3-bit Ripple-Carry Adder (RCA)
- Superposition input experiments
- Execution on real IBM Quantum hardware

The work demonstrates how classical Boolean arithmetic can be transformed into reversible quantum circuits using CNOT and Toffoli gates.

---

## Implemented Tasks

### 1. Half Adder
- Constructed using reversible logic
- Verified via statevector and probability plots
- Interpreted computational basis outputs

### 2. Full Adder
- Built by cascading two Half Adders
- Converted to reversible quantum implementation
- Analyzed using statevector and Q-sphere visualizations

### 3. Superposition Experiment
- Input qubit prepared using Hadamard gate
- Observed superposed output states
- Verified linearity of quantum operations

### 4. 3-bit Ripple-Carry Adder
- Constructed by chaining reversible Full Adders
- Carry propagated across stages
- Ancilla qubits uncomputed for full reversibility
- Verified on simulator

### 5. Execution on Real Quantum Hardware
- Circuit executed on IBM Quantum backend (`ibm_torino`)
- Observed hardware noise effects
- Compared simulator vs real-device results

### 6. ID-based Addition
Using student ID `202515470`:

- \( A = 7 \)
- \( B = 1 \)
- Binary addition performed using 3-bit RCA

---

## Files Included

- `COE530_Assignment1_FerasAlsayigh_g202515470.ipynb`  
  Jupyter notebook containing full implementation and experiments.

- `assignment.pdf`  
  Assignment description.

- `documentation.pdf`  
  Detailed report including circuit diagrams and results.

---

## Technologies Used

- Python
- Qiskit
- IBM Quantum Runtime
- Aer Simulator
- IBM Quantum Hardware

---

## Key Concepts Demonstrated

- Reversible computation
- Quantum statevector interpretation
- Superposition and linearity
- Carry propagation in quantum circuits
- Noise effects.

---

## Author

Feras Alsayigh  
MSc Quantum Computing Candidate – KFUPM  
Under the supervision of Dr. Muhamad Felemban
