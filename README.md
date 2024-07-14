# awesome-quantum-computing
 A curated list of awesome Quantum Computing frameworks, libraries and software. 

# Frameworks

Full-stack software frameworks for constructing circuits and executing on quantum computing hardware.

* [Qiskit](https://github.com/Qiskit) - IBM's open-source SDK for working with quantum computers at the level of extended quantum circuits, operators, and primitives.
* [Cirq](https://github.com/quantumlib/Cirq) - Google's python framework for creating, editing, and invoking Noisy Intermediate Scale Quantum (NISQ) circuits.
* [Pyquil](https://github.com/rigetti/pyquil) - Rigetti's python library for constructing and executing programs using Quil.
* [Pennylane](https://github.com/PennyLaneAI/pennylane) - Xanadu's cross-platform Python library for quantum computing, quantum machine learning, and quantum chemistry.

# Simulators

Simulators for quantum circuits. Determine the output of a quantum circuit using a classical computer.

* [QVM](https://github.com/quil-lang/qvm) - A high-performance state-vector simulator for Quil programs. Written in common-lisp.
* [Qiskit Aer](https://github.com/Qiskit/qiskit-aer) - Qiskit simulation package. Provides an interface to numerous backends including state-vector, tensor-network and matrix-product-state simulators. Supports noise and GPUs depending on the backend.
* [Qsim](https://github.com/quantumlib/qsim) - A high-performance state-vector simulator which supports Cirq. Supports noise and GPUs.
* [Pennylane Lightning](https://github.com/PennyLaneAI/pennylane-lightning) - High-performance state-vector simulator written in C++ for use with Pennylane. Offers some unique features around GPUs and differentiation.
* [Qutip-qip](https://github.com/qutip/qutip-qip) - Circuit simulation extension of the general-purpose Qutip package. Offers unique features around noise and pulse-level simulation.
* [CuQuantum](https://github.com/NVIDIA/cuQuantum) - Nvidia's cuQuantum sdk which provides GPU-based simulation of quantum circuits. State-vector and tensor-network are supported. Fairly low-level and can used as a backend by Qiskit Aer and others.
* [qHiPSTER](https://github.com/intel/intel-qs) - Intel's high-performance quantum simulator. State-vector simulator highly optimized for multiple CPUs.
* [QRack](https://github.com/unitaryfund/qrack) - Comprehensive, GPU accelerated framework from the unitary fund.
* [ITensor](https://github.com/ITensor/ITensors.jl) - State-of-the-art tensor network simulations written in Julia.
