# awesome-quantum-computing

 A curated list of awesome Quantum Computing frameworks, libraries and software. This list is exclusively focused on open-source software libraries.

# Frameworks

Full-stack software frameworks for constructing circuits and executing on quantum computing hardware.

* [Qiskit](https://github.com/Qiskit) - IBM's open-source SDK for working with quantum computers at the level of extended quantum circuits, operators, and primitives.
* [Cirq](https://github.com/quantumlib/Cirq) - Google's python framework for creating, editing, and invoking Noisy Intermediate Scale Quantum (NISQ) circuits.
* [Pyquil](https://github.com/rigetti/pyquil) - Rigetti's python library for constructing and executing programs using Quil.
* [Pennylane](https://github.com/PennyLaneAI/pennylane) - Xanadu's cross-platform Python library for quantum computing, quantum machine learning, and quantum chemistry.
* [qBraid](https://github.com/qBraid/qBraid) - A platform-agnostic quantum runtime framework
* [Ocean](https://github.com/dwavesystems/dwave-ocean-sdk) - SDK for D-Wave's quantum annealers.

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
* [QuEST](https://github.com/QuEST-Kit/QuEST) - A multithreaded, distributed, GPU-accelerated simulator of quantum computers

# Compilers

Compilers transform logical quantum circuits 

* [QuilC](https://github.com/quil-lang/quilc) - A full-stack compiler written in common lisp for the Quil language.qis
* [Qiskit.compiler](https://github.com/Qiskit/qiskit/tree/main/qiskit/compiler) - Qiskit's built-in full stack compiler with dozens of compilation passes.
* [Tket](https://github.com/CQCL/tket) - C++-based full-stack quantum compiler written by Quantinuum.
* [BQSKit](https://github.com/BQSKit/bqskit) - Berkeley Quantum Synthesis Toolkit is a full-stack quantum compiler that uses numerical and approximate methods to find high-performing compilations.
* [Cirq.transformers](https://github.com/quantumlib/Cirq/tree/main/cirq-core/cirq/transformers) - Cirq's built-in transformers offer a variety of compilation passes, but does not include routing.

# Error Mitigation

Error mitigation can mitigate the impact of errors in quantum devices.

* [Mitiq](https://github.com/unitaryfund/mitiq) - An open source toolkit for implementing error mitigation techniques on most current intermediate-scale quantum computers from the Unitary Fund.
* [Qermit](https://github.com/CQCL/Qermit) - Python module for running error-mitigation protocols with the pytket quantum SDK
* [PyIBU](https://github.com/sidsrinivasan/PyIBU) - A scalable implementation of iterative Bayesian unfolding for measurement error mitigation.
* [AutomatedPERTools](https://github.com/benmcdonough20/AutomatedPERTools) - Autonomous error mitigation based on probabilistic error reduction.

# Optimal Control

Libraries for controling quantum systems and realizing gates.

* [Piccolo](https://github.com/kestrelquantum/Piccolo.jl) - Quantum optimal control using the Pade Integrator COllocation (PICO) method.
* [SCQubits](https://github.com/scqubits/scqubits) - An open-source Python library for simulating superconducting qubits.
* [C3](https://github.com/q-optimize/c3) - An integrated tool-set for Control, Calibration and Characterization.
* [Quandary](https://github.com/LLNL/quandary) - Quandary implements an optimization solver for open and closed optimal quantum control.
* [Qiskit Dynamics](https://github.com/Qiskit-Extensions/qiskit-dynamics) - Qiskit Dynamics is an open-source project for building, transforming, and solving time-dependent quantum systems in Qiskit.
* [Qibo](https://github.com/qiboteam/qibo) - Qibo is an open-source full stack API for quantum simulation and quantum hardware control.


# Applications

Libraries for applying quantum algorithms.
