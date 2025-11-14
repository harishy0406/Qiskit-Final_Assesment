## 🚀 Final Assessment-1: Deutsch–Jozsa Algorithm (Qiskit)

This python notebook implements the **Deutsch–Jozsa algorithm** for a **3-qubit input function** using Qiskit.

### ✨ Features Included:
- 🟦 Construction of **constant** and **balanced** oracle functions  
- ⚙️ Full DJ circuit (Initialization → Hadamards → Oracle → Measurement)
- 🧪 Simulation using **AerSimulator (1024 shots)**
- 📊 Visualizations:
  - 🧩 Circuit diagrams  
  - 📈 Measurement histograms  
  - 🌐 Bloch sphere plots  
  - 🏙️ Statevector city plots
- ⚡ Transpilation benchmarking across **optimization levels 0–3**, comparing:
  - 📏 Circuit depth  
  - 🔢 Gate count  
  - ⏱️ Execution time
- ✅ Final analysis confirming:
  - Correct algorithm behavior  
  - Optimization trade-offs  

---

## 🚀 Final Assessment-2: Quantum Circuit Optimization & Benchmarking

This python notebook builds and benchmarks a **4-qubit parameterized quantum circuit** using Qiskit.

### 🔍 Key Features:
- 🎯 Random generation of **10 parameter sets**
- 🧮 Execution & measurement of each parameterized circuit
- 🔁 Fidelity calculation using `state_fidelity()`
- 🔧 Optimization via **transpilation levels 0, 1, 2, 3**
- 📊 Collected metrics:
  - ⏱️ Execution time  
  - 📏 Circuit depth  
  - 🔢 Gate count  
  - 🎛️ Fidelity vs. ideal statevector
- 🖼️ Visualizations:
  - ⚡ Execution time vs optimization level  
  - 📉 Depth vs fidelity trade-off  
  - 📈 Output state histograms
- 🏆 Benchmark summary identifying the **best optimization level** for performance-to-fidelity ratio

---

### 📝 Summary
This repository contains two advanced Qiskit projects focusing on **quantum algorithm implementation**, **simulation**, and **circuit optimization benchmarking**.  
Perfect for understanding both **theory** and **practical performance analysis** in quantum computing.
