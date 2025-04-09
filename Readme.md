# Quantum Computing

Welcome to the **Quantum Computing** repository! This project showcases solutions to four distinct quantum computing tasks, implemented using Python and quantum computing libraries like Qiskit and Cirq. Each task explores fundamental quantum concepts such as superposition, entanglement, and measurement, with simulations and visualizations to verify the results.

The goal of this repository is to provide clear, reproducible examples of quantum circuits, making it a valuable resource for learners, researchers, and enthusiasts in quantum computing.

---

## Table of Contents
- [Overview](#overview)
- [Tasks](#tasks)
  - [Task 1: Forced Superposition](#task-1-forced-superposition)
  - [Task 2: Entanglement Witness](#task-2-entanglement-witness)
  - [Task 3: Opposite-Measurement Entanglement](#task-3-opposite-measurement-entanglement)
  - [Task 4: Quantum Coin Flip Game](#task-4-quantum-coin-flip-game)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

---

## Overview
This repository contains four Jupyter notebooks, each solving a unique quantum computing challenge. The tasks range from creating entangled states with specific measurement outcomes to simulating a quantum game with probabilistic twists. Results are verified through simulations (e.g., 1000 shots) and visualized using histograms or bar plots.

---

## Tasks

### Task 1: Forced Superposition
**Objective**: Create a 2-qubit circuit where Qubit 0 starts in |+⟩ (superposition), Qubit 1 starts in |1⟩, and they are entangled so Qubit 0’s measurement is always the opposite of Qubit 1’s.

**Implementation**: Uses H (Hadamard), X (NOT), and CX (Controlled-NOT) gates. Simulated with 1000 shots, showing only '01' and '10' outcomes in the histogram.

**File**: `Forced Superposition.ipynb`

---

### Task 2: Entanglement Witness
**Objective**: Test if two qubits remain entangled after a probabilistic error. Prepares a Bell state (|00⟩ + |11⟩)/√2, applies an X gate to one qubit with 20% probability, and measures one qubit 1000 times.

**Implementation**: If the output is not 50/50, entanglement is broken. Demonstrates how modifying one qubit disrupts the entangled state.

**File**: `Entanglement Witness.ipynb`

---

### Task 3: Opposite-Measurement Entanglement
**Objective**: Build a 2-qubit circuit where measuring one qubit always yields the opposite of the other (e.g., '01' or '10', never '00' or '11').

**Implementation**: Entangles qubits using H and CX gates. Verified with 1000 shots, histogram confirms only '01' and '10' outcomes.

**File**: `opposite_entanglement.ipynb`

---

### Task 4: Quantum Coin Flip Game
**Objective**: Simulate a game where Alice prepares a qubit in |+⟩, and Bob measures it in either X-basis (|+⟩/|-⟩) or Z-basis (|0⟩/|1⟩). Bob wins on |+⟩ or |0⟩; Alice wins otherwise. Includes a twist where Bob entangles his basis choice.

**Implementation**: Runs 500 trials for both basic and entangled versions, calculating win rates. Visualizes results with a bar plot.

**File**: `Quantum Coin Flip Game.ipynb`

---

## Technologies
- **Python 3.8+**: Core programming language.
- **Qiskit**: Used for Tasks 1, 2, and 3 (quantum circuit design and simulation).
- **Cirq**: Used for Task 4 (alternative quantum computing framework).
- **Matplotlib**: Visualization of results (histograms and bar plots).
- **NumPy**: Random number generation and data handling.
- **Jupyter Notebook**: Interactive environment for running and documenting experiments.

---

## Installation
To run these experiments locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Ofgeha-Gelana/Quantum-Computing.git
   cd Quantum-Computing


   ## **Essay Question**
[**Essay**](https://medium.com/@ofgehagelana2019/how-entanglement-and-superposition-enable-quantum-speedups-09e7028671cf)