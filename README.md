# Mapping Quantum Circuits to IBM QX Architectures
---

### This notebook is a demonstration of the mapping for any Quantum Circuit to IBM's QX architecture in quantum computing using qiskit. It was used in this [paper](https://ieeexplore.ieee.org/document/8382253). 

I illustrate the two steps that are required for the mapping process based on the paper approach using qiskit. The mapping process is then can be entered into A* or genetic algorithm to perform more optimization. The proposed approach can determine a mapping for quantum circuits within seconds in most cases whereas IBM’s solution requires more than 1 h to determine a solution for several cases. In the upcoming notebooks, I shall implement some important applications.

----
### Software Requirements:
```
pip install qiskit --upgrade
```
