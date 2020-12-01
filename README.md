# IBM Quantum Awards: Open Science Prize

This is the repository for the IBM Quantum Awards: Open Science Prize. You can read more about it and register [here](https://www.ibmquantumawards.com/), and read the IBM Quantum announcement [here](https://www.ibm.com/blogs/research/2020/11/open-science-prize/).

# Objective

The IBM Quantum Awards: Open Science Prize aims to solve two problems at the forefront of quantum computation based on superconducting qubits:

1. **Creating better SWAP gates** Typically, [SWAP](https://qiskit.org/textbook/ch-gates/more-circuit-identities.html#2.-Swapping-Qubits-) gates are implemented using three controlled-NOT (CNOT or CX) gates. This can be expensive, as the limiting gate error comes from the 2-qubit gates. The goal here is to create the best SWAP gate with a reduction in the infidelity of at least 50% compared with a traditional SWAP implemented using three standard CNOT gates, as estimated using randomized benchmarking techniques outlined in [this Jupyter notebook](ibmquantum-swap-gate-challenge.ipynb). **Award: $50,000**

2. **Creating larger graph states with better fidelity** Graph states entangle all involved qubits, and these entangled quantum states could be important for various applications, particularly those related to error correction, in the near future. The goal here is to create the largest graph states using the same benchmarking and error mitigation techniques that are also used to improve the individual quantum gates, ultimately looking for the best fidelity graph state with at least a 50% reduction in the infidelity as estimated by stabilizer measurements outlined in [this Jupyter notebook](ibmquantum-graph-states-challenge.ipynb). **Award: $50,000**

# Open Science

The goal of the Prize is to make significant progress on challenges at the forefront of quantum computation by doing science in the open. The resulting solutions will be open-sourced for the benefit of the entire quantum computing community.