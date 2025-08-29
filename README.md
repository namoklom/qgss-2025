# QGSS 2025 (Quantum Global Summer School) Complete Solutions (Lab 0 - 4)

## 👤 Author

| Name            | Role              | LinkedIn                                      |
|-----------------|-------------------|-----------------------------------------------|
| Jason Emmanuel  | Quantum Computing Engineer  | [linkedin.com/in/jasoneml](https://www.linkedin.com/in/jasoneml/) |

This repository serves as a technical archive of my work during the **Quantum Global Summer School (QGSS) 2025**, focusing on both the theoretical framework and the practical implementation of quantum computing concepts. The materials here are not only a record of exercises but also a structured workflow that transitions from fundamental principles to advanced quantum algorithms. The work emphasizes the use of **Python, qBraid, and Qiskit** as the primary tools for quantum circuit design, simulation, and visualization, while also incorporating supporting libraries for linear algebra, optimization, and data analysis. 

The repository is organized to highlight the **progressive nature of quantum computing education**: starting with environment setup and basic gate operations, advancing through canonical algorithms, exploring the limitations imposed by noise and decoherence, and culminating in hybrid variational methods designed for NISQ (Noisy Intermediate-Scale Quantum) devices. Each stage is approached with a combination of **mathematical rigor, circuit-level implementation, and empirical validation** through simulation. By systematically integrating quantum theory with computational experiments, this project reflects a workflow similar to what is practiced in modern quantum research and industry applications.

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

<img width="617" height="251" alt="image" src="https://github.com/user-attachments/assets/37baf640-18ff-44cf-b05f-b47e583b602b" />

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

<img width="1125" height="303" alt="image" src="https://github.com/user-attachments/assets/c9ebdfa4-37af-4901-a4f1-b8083c467248" />

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

<img width="855" height="470" alt="image" src="https://github.com/user-attachments/assets/8b87f9af-f87d-4656-bdc2-4e5abe292769" />

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

<img width="2084" height="1030" alt="image" src="https://github.com/user-attachments/assets/a9453236-ce14-4640-8059-ff632810cd8b" />

<img width="11862" height="2170" alt="image" src="https://github.com/user-attachments/assets/e6efee3a-f8ad-4108-9e25-25141f003ad9" />

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

<img width="1974" height="1126" alt="image" src="https://github.com/user-attachments/assets/dc98fc1b-c291-43e6-b140-db5312854667" />

<img width="3918" height="1145" alt="image" src="https://github.com/user-attachments/assets/0a50492e-3120-4f5d-8dfd-157e41bd8364" />

---

## ✨ Key Features
- End-to-end **quantum curriculum**: setup → basics → algorithms → error correction → applications.  
- Detailed **Jupyter notebooks** for each lab.  
- Rich **visualizations** of circuits, Bloch spheres, and probability distributions.  
- Experiments with **noise models** and **hybrid quantum-classical workflows**.  

---

## 🛠️ Tools & Tech Stack

| Tool / Library   | Usage / Purpose |
|------------------|-----------------|
| **Python 3.11**  | Primary programming language for all labs |
| **qBraid** | Interactive environment for running experiments & documenting results |
| **Qiskit (Terra, Aer, Ignis, Aqua)** | Quantum SDK for building, simulating, and executing circuits |
| **Matplotlib & Seaborn** | Data visualization, probability distributions, and circuit analysis |
| **Qiskit Visualization (Circuit Drawer, Bloch Sphere)** | Visualize quantum states, circuits, and Bloch sphere representations |
| **NumPy** | Linear algebra and tensor operations for qubits and gates |
| **SciPy Optimizers (COBYLA, SPSA)** | Classical optimizers used in VQE and QAOA |

---

# Launch on qBraid

qBraid is an official Jupyter Lab cloud platform host for the Qiskit Global Summer School this year. Follow our quick tutorial [here](https://docs.qbraid.com/lab/user-guide/qgss-2025) to get started with no set-up, installations, or hassle.

To open the QGSS files, labs, and resources directly on qBraid, click this button:

[<img src="https://qbraid-static.s3.amazonaws.com/logos/Launch_on_qBraid_white.png" width="150">](https://account.qbraid.com/?gitHubUrl=https://github.com/qiskit-community/qgss-2025.git&api=v2)


