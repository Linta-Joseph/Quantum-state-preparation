# Quantum-state-preparation

Implementation of the quantum state preparation problem in Qiskit. Given a $2^{n}$ dimensional vector of complex amplitudes, with $\| \psi \|_2=1$ , the code constructs a $U$ such that $$U\ket{0}_{n} = \sum_{x=0}^{2^n-1}\psi_{x}\ket{x}_n$$. 