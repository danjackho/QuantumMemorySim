# QuantumMemorySim
A set of python jupyter notebooks showcasing the quantum memory numerical simulation and the evolutionary optimisation algorithms applied to a novel 4-level quantum memory protocol in my MSc thesis.

The 'QM 3.0 - Rydberg' notebook demonstrates how the numerical simulation is used. This includes simulating the storage and retrieval mappings and computing the storage efficiency, memory efficiency, and input-output signal pulse overlap metric.

The 'QM 3.0 - Genetic Optimisation - ORCA + Rydberg' notebook uses the numerical simulation developed in the previous notebook in a black-box genetic optimisation algorithm to produce optimal primary and secondary control pulse-shapes for the storage and retrieval processes. 

Similarly, the 'QM 3.0 - Particle Swarm Optimisation - ORCA + Rydberg' notebook does the same however applies a black-box genetic optimisation algorithm to produce the optimal primary and secondary control pulse-shapes for the storage and retrieval processes. 

Both black-box evolutionary algorithms are applied to the optimisation of Gaussian control pulse-shapes as well as arbitarary control pulse-shapes.
