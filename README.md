# 🌐 QGSS 2025 — Quantum Global Summer School

This repository documents my learning journey during **Quantum Global Summer School (QGSS) 2025**, focusing on **Quantum Computing fundamentals, algorithms, and applications**.

Each lab builds progressively — from setting up the environment, understanding quantum states, implementing algorithms, addressing noise/error correction, to applying variational methods for real-world problems.  

---

## 📖 Lab Breakdown & Systematic Explanations

### 🔹 Lab 0 — Environment Setup
**Objective:** Prepare the quantum development environment.  
**Techniques:**
- Installed **Python 3.11** with a clean virtual environment.
- Configured **Jupyter Notebook** for interactive exploration.
- Installed **Qiskit** (IBM’s open-source quantum SDK).
- Verified installation by running a sample Bell state circuit.  

**Outcome:**  
A fully functional environment capable of running simulations locally and optionally connecting to **IBM Quantum Experience** backend.

---

### 🔹 Lab 1 — Quantum Basics
**Objective:** Build strong intuition on quantum states and operators.  
**Techniques:**
- Represented **qubits** mathematically as complex vectors (`|0⟩`, `|1⟩`).
- Applied **single-qubit gates** (Pauli-X, Y, Z; Hadamard; Phase gates).
- Constructed **multi-qubit systems** with tensor products.
- Visualized states on the **Bloch Sphere**.
- Measured qubits to understand probabilistic outcomes.  

**Outcome:**  
- Learned how qubits evolve under unitary transformations.  
- Developed simple circuits to generate **superposition** and **entanglement**.  

---

### 🔹 Lab 2 — Quantum Algorithms
**Objective:** Implement foundational quantum algorithms.  
**Techniques:**
- **Superposition & Entanglement** with Hadamard + CNOT gates.  
- **Deutsch–Jozsa Algorithm**: determining constant vs balanced functions with a single query.  
- **Grover’s Algorithm**: quadratic speed-up in unstructured search using Oracle + Diffusion operators.  
- Simulated circuits with Qiskit Aer for reproducible outputs.  

**Outcome:**  
- Demonstrated how quantum algorithms outperform classical ones for specific problems.  
- Developed reusable circuit templates for algorithmic testing.  

---

### 🔹 Lab 3 — Quantum Error Correction
**Objective:** Understand noise in quantum systems and explore error mitigation.  
**Techniques:**
- Modeled **quantum noise channels** (bit-flip, phase-flip, depolarizing).  
- Implemented **3-qubit repetition code** for bit-flip error detection/correction.  
- Simulated noisy circuits using Qiskit’s **NoiseModel**.  
- Evaluated performance with and without error correction.  

**Outcome:**  
- Quantified the trade-off between redundancy and error resilience.  
- Demonstrated that simple codes can significantly improve fidelity in noisy simulations.  

---

### 🔹 Lab 4 — Advanced Applications
**Objective:** Explore variational algorithms for near-term quantum devices (NISQ era).  
**Techniques:**
- Implemented **Variational Quantum Eigensolver (VQE)** to approximate ground state energies in molecular Hamiltonians.  
- Applied **Quantum Approximate Optimization Algorithm (QAOA)** for combinatorial optimization (e.g., MaxCut problem).  
- Combined classical optimizers (COBYLA, SPSA) with parameterized quantum circuits.  
- Benchmarked convergence and performance against classical solvers.  

**Outcome:**  
- Showcased how hybrid quantum-classical algorithms can solve problems beyond reach of brute-force classical methods.  
- Highlighted the role of quantum computing in **chemistry, optimization, and finance**.  

---

## 🛠️ Tech Stack
- **Language:** Python 3.11  
- **Environment:** Jupyter Notebook  
- **Quantum SDK:** Qiskit (Terra, Aer, Ignis, Aqua modules)  
- **Visualization:** Matplotlib, Seaborn, Qiskit Bloch Sphere & Circuit Drawers  
- **Classical Optimizers:** SciPy, NumPy  

---

## ✨ Key Features
- End-to-end **quantum curriculum**: setup → basics → algorithms → error correction → applications.  
- Detailed **Jupyter notebooks** for each lab.  
- Rich **visualizations** of circuits, Bloch spheres, and probability distributions.  
- Experiments with **noise models** and **hybrid quantum-classical workflows**.  

---

# Launch on qBraid

qBraid is an official Jupyter Lab cloud platform host for the Qiskit Global Summer School this year. Follow our quick tutorial [here](https://docs.qbraid.com/lab/user-guide/qgss-2025) to get started with no set-up, installations, or hassle.

To open the QGSS files, labs, and resources directly on qBraid, click this button:

[<img src="https://qbraid-static.s3.amazonaws.com/logos/Launch_on_qBraid_white.png" width="150">](https://account.qbraid.com/?gitHubUrl=https://github.com/qiskit-community/qgss-2025.git&api=v2)


