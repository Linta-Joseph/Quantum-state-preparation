# Quantum-state-preparation

Implementation of the quantum state preparation problem in Qiskit. Given a $2^{n}$ dimensional vector of complex amplitudes, with $\lVert \psi \rVert_2 = 1$, the code constructs a $U$ such that

$$U|0\rangle_{n} = \sum_{x=0}^{2^{n}-1}\psi_{x}|x\rangle_{n}.$$