# Qiskit Global Summer School 2025

This repository contains my complete work for the [IBM Quantum Global Summer School 2025 (QGSS25)](https://github.com/qiskit-community/qgss-2025), hosted by IBM Quantum and Qiskit. This documentation serves as both a learning record and a reference for future quantum computing students.

## 🎓 About QGSS 2025

The **Qiskit Global Summer School 2025** theme was **"The Past, Present and Future of Quantum Computing"** - exploring the evolution from early quantum concepts to cutting-edge fault-tolerant quantum computing implementations.

## 🧠 Topics Covered & Mastered

### **Lab 0: Quantum Computing Foundations**
- Quantum circuit design and basic gates
- Superposition and entanglement principles  
- Bloch sphere visualization
- Introduction to Qiskit ecosystem

### **Lab 1: Advanced Quantum Circuits**
- Multi-qubit operations and measurements
- Quantum algorithm implementations
- Hardware-aware transpilation
- Real device execution with `QiskitRuntimeService`

### **Lab 2: Quantum Phenomena & Applications** 
- Double-slit experiment quantum simulation
- Quantum entanglement demonstrations
- CHSH game implementation and Bell inequality violations
- Quantum advantage exploration

### **Lab 3: Quantum Chemistry & Molecular Simulation**
- **VQE (Variational Quantum Eigensolver)** for molecular ground states
- **N₂ molecule simulation** using cc-pVDZ basis sets
- **UCCSD ansatz** implementation and optimization
- **IBM hardware backend selection** (IBM Torino) with error analysis
- **LUCJ (Low-rank Unitary Coupled Cluster with Jastrow) ansatz** extensions
- Real quantum hardware execution for chemistry problems

### **Lab 4: Quantum Error Correction (Advanced)**
- **3-qubit bit-flip code** syndrome decoding
- **[[7,1,3]] Steane code** complete implementation
- **Syndrome measurement circuits** with ancilla qubits
- **Toric code construction** on 144-qubit toroidal lattices
- **Gross code implementation** with long-range connections
- **CSS code theory** and logical qubit counting
- **Topological quantum error correction** principles

### IBM Quantum Network Topology

The quantum chemistry experiments in Lab 3 utilized IBM's heavy-hex lattice architecture:

![IBM Quantum Network Topology](images/network%20topo.png)

*Figure: IBM Quantum backend connectivity graph showing the heavy-hex lattice structure used for optimal qubit layout selection in quantum chemistry simulations.*

## 📁 Repository Structure

| Folder/File | Description | Key Achievements |
|-------------|-------------|------------------|
| `lab0/` | Quantum computing foundations | ✅ Basic circuit mastery |
| `lab1/` | Advanced quantum circuits | ✅ Multi-qubit operations |
| `lab2/` | Quantum phenomena & games | ✅ CHSH game & Bell violations |
| `Lab2 (1).ipynb` | Extended quantum applications | ✅ Advanced implementations |
| `lab3/` | **Quantum Chemistry** | ✅ **VQE, UCCSD, LUCJ ansatz** |
| `lab4/` | **Quantum Error Correction** | ✅ **Toric & Gross codes** |
| `.gitignore` | Repository management | Clean project structure |
| `README.md` | Project documentation | This comprehensive guide |

## 🚀 Technical Environment

**Platform**: [QBraid](https://qbraid.com/) - Integrated quantum development environment

**Technologies Used**:
- **Python 3.11** with Jupyter Notebooks
- **Qiskit** (latest version) - IBM's quantum computing framework
- **Qiskit Runtime** - Hardware execution service  
- **IBM Quantum Network** access for real device testing
- **Advanced Libraries**: 
  - `ffsim` for quantum chemistry simulations
  - `pyscf` for molecular orbital calculations
  - Custom quantum error correction utilities

**Hardware Access**:
- **IBM Torino** (133-qubit heavy-hex lattice) for quantum chemistry
- Various IBM Quantum Network backends for error correction testing

## 📊 Learning Outcomes

### **Theoretical Understanding**
- **Quantum mechanics foundations** and computational applications
- **Quantum chemistry theory** and electronic structure calculations  
- **Quantum error correction** principles and topological protection
- **CSS codes, stabilizer formalism**, and fault-tolerant computing

### **Practical Skills**
- **Quantum algorithm implementation** from theory to hardware
- **Real quantum device programming** and hardware-aware optimization
- **Advanced debugging** of quantum circuits and error correction codes
- **Scientific computing** with quantum chemistry and many-body systems

### **Research-Level Competencies**
- **Cutting-edge quantum error correction** (toric codes, gross codes)
- **Variational quantum algorithms** for chemistry and optimization
- **Hardware-software co-design** for NISQ applications
- **Systematic approach** to complex quantum computing problems

## 🔬 Research Connections

- **Quantum information theory** and error correction
- **Computational quantum chemistry** and molecular simulation  
- **Topological quantum computing** and fault-tolerant architectures
- **Near-term quantum algorithms** and hardware optimization

## 📬 Regards

**GitHub**: [@Ansal06](https://github.com/Ansal06)  
**Email**: aspphy2997@gmail.com
---

*This repository represents a comprehensive learning journey through modern quantum computing - from foundational principles to research implementation examples. The labs hone your theoretical understanding and practical programming skills essential for quantum information research.*

**Note**: Some notebooks require QBraid environment or Qiskit Runtime access for full execution. 
