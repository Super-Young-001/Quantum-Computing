# Module 1 Superposition and Qubit

### Classical bit

exclusive state (either 0 or 1)

### Quantum bit 

superposition state with probability

### Qubit Notation

##### 		1. Single qubit notation

$$
\
|\psi\rangle = \alpha_0|0\rangle + \alpha_1|1\rangle
$$

##### 		2. Multi-qubit Notation

$$
\
|\psi_2\psi_1\rangle=\alpha_{00}|00\rangle+\alpha_{01}|01\rangle+\alpha_{10}|10\rangle+\alpha_{11}|11\rangle$$

- With N qubits, we can concurrently represent superposition over 2N states
- Measurement Collapses the Qubit to One of the Basis States

$$
|\alpha_0|^2 + |\alpha_1|^2 = 1
$$

### Polarization of Light

Horizontally - Vertically - Diagonally

### Basis States

1. Standard /Computational Basis |0> and |1>
2. Hadamard Basis |+>and |->

Superposition Depends on the Basis States(A given qubit state may or may not be in superposition depending on the basis states.).

### BB-84: Goal Secure key transfer from Alice to Bob

- Step 1: Alice sends in a randomly selected Basis State

- Step 2: Bob receives a Phoron and decodes in a randomly selected Basis State

- Step 3: Alice and Bob check if they used the same Basis State. If not, discard qubit

  <img src="assets\image-20260629002958205.png" alt="image-20260629002958205" style="zoom: 33%;" />

Detect tampering by comparing and discarding some transferred bits.

Block Sphere: Generalized Model























