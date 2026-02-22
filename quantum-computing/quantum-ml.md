# Quantum Machine Learning — Algorithms & Applications

## Overview

Quantum machine learning (QML) applies quantum computing to ML tasks, potentially offering speedups for specific problems. The field is at an early but rapidly advancing stage.

## Key QML Algorithms

### 1. Quantum Support Vector Machine (QSVM)
- **How:** Maps data to quantum feature space using quantum kernels
- **Advantage:** Exponentially larger feature space exploration
- **Status:** Demonstrated on real quantum hardware (IBM, Quantinuum)
- **Use case:** Classification tasks with complex decision boundaries

### 2. Variational Quantum Eigensolver (VQE)
- **How:** Hybrid classical-quantum optimization for finding ground states
- **Advantage:** Near-term compatible (NISQ-friendly)
- **Status:** Applied to molecular simulation, optimization problems
- **Use case:** Drug discovery, materials science, chemistry

### 3. Quantum Approximate Optimization Algorithm (QAOA)
- **How:** Parameterized quantum circuits for combinatorial optimization
- **Advantage:** Potential speedup on NP-hard problems
- **Status:** Active research, limited practical advantage shown so far
- **Use case:** Portfolio optimization, logistics, scheduling

### 4. Quantum Neural Networks (QNN)
- **How:** Parameterized quantum circuits acting as trainable models
- **Challenge:** Barren plateau problem — gradients vanish exponentially
- **Status:** Theoretical work on expressibility and trainability
- **Use case:** Research stage, no clear practical advantage yet

### 5. Quantum Reservoir Computing
- **How:** Uses quantum system dynamics as a computational reservoir
- **Advantage:** No training of quantum circuit needed
- **Status:** Emerging as practical near-term approach
- **Use case:** Time series prediction, chaotic system modeling

### 6. Quantum Boltzmann Machines
- **How:** Quantum version of classical RBMs using quantum tunneling for sampling
- **Advantage:** Potentially faster thermalization and sampling
- **Status:** Theoretical with small-scale experiments
- **Use case:** Generative modeling, feature learning

### 7. Quantum Principal Component Analysis
- **How:** Exponentially faster eigenvalue estimation for density matrices
- **Advantage:** Exponential speedup (with caveats on data loading)
- **Status:** Requires fault-tolerant hardware
- **Use case:** Dimensionality reduction on quantum data

## Frameworks & Tools

| Framework | Provider | Language | Features |
|-----------|----------|----------|----------|
| Qiskit ML | IBM | Python | QSVMs, QNNs, VQE, quantum kernels |
| TensorFlow Quantum | Google | Python | TF integration, hybrid models |
| PennyLane | Xanadu | Python | Differentiable quantum computing |
| Cirq | Google | Python | Low-level circuit design |
| Amazon Braket SDK | AWS | Python | Multi-backend quantum ML |
| Paddle Quantum | Baidu | Python | Quantum NLP, chemistry |

## Current Limitations

1. **Data loading bottleneck** — Getting classical data into quantum states is expensive
2. **Barren plateaus** — Training QNNs becomes exponentially hard with more qubits
3. **Noise** — Current hardware errors limit circuit depth
4. **Limited qubits** — Most algorithms need more qubits than available
5. **Dequantization** — Some "quantum speedups" have been matched classically (Tang, 2018)

## Where QML Might Win

| Application | Why Quantum Helps | Timeline |
|-------------|-------------------|----------|
| Drug discovery | Molecular simulation is naturally quantum | 3–5 years |
| Materials science | Electronic structure calculations | 3–5 years |
| Financial optimization | Combinatorial portfolio problems | 5–10 years |
| Cryptography | Shor's algorithm breaks RSA | 10+ years |
| Quantum data | ML on data from quantum experiments | Now |

## Key Papers

1. Havlicek et al. (2019) — "Supervised learning with quantum-enhanced feature spaces" — *Nature*
2. Abbas et al. (2021) — "The power of quantum neural networks" — *Nature Computational Science*
3. Huang et al. (2022) — "Quantum advantage in learning from experiments" — *Science*
4. Cerezo et al. (2021) — "Variational quantum algorithms" — *Nature Reviews Physics*
5. Tang (2018) — "A quantum-inspired classical algorithm for recommendation systems" — *STOC*

---

*Updated: February 2025*
