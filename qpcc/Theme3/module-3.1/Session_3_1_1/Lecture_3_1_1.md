# Lecture 3.1.1

**Intro**

- Call back to Theme 1 historical timeline.
- Everything represented by binary, 0/1, on/off.
- Draw contrast/similarity with qbits, 0ish and 1ish.

**Binary Data**

- Base 10 <-> Base 2

$$
\begin{aligned}
146 & = 1\times100 + 4\times10 + 6\times1 \\
& = 1\times10^2 + 4\times10^1 + 6\times10^0
\end{aligned}
$$

$$
\begin{aligned}
10010010_{2} & = 1\times2^7 + 0\times2^6 + 0\times2^5 + 1\times2^4 + 0\times2^3 + 0\times2^2 + 1\times2^1 + 0\times2^0 \\
& = 128 + 16 + 2 \\
& = 146
\end{aligned}
$$

![146 Binary and Decimal](images/binary.png)


- Adding in Binary
- Classical AND, OR, and XOR gates (universality)
- Classical half-adder: Highlight how there is liberal copying of bits and how 2 bits can go into a gate and only one come out (cloning and non-reversibility)

**Physical Representation**

- Over years smaller and smaller
- Transistors are use quantum effects in their physical implementation   

**Quantum Difference**

- Brief introduction to the properties that give an increased scope (qubit superposition, entanglement, etc)
- Complexity Classes

**Qubits without maths**

- Introduction as an abstract concept without mathematics (perhaps circles), maybe with an experiment like Mach-Zender/Stern Gerlach.
- A discussion on measurement and what is different.
- Can even discuss some gate actions (Paulis and Hadamard) on qubits.
- Discussion about what quantum properties such as coherence can add to computing (a thought experiment demonstrating Bell’s inequalities without mentioning them can be discussed here). Maybe the way to go is a light discussion like in https://www.youtube.com/watch?v=zcqZHYo7ONs.

**Quantum computers from a physicist point of view**

- Origin of quantum computers: classical computers are not suitable for physics simulations of highly-correlated systems (many-body problems complexity, solid state/lattice models)
- Annealing: quantum systems to simulate quantum systems. 1 to 1 qubit-particle mapping   