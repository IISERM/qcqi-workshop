---
title: "Scientists write fiction"
subtitle: "Session 1 for QCQI Workshop 2023"
author: "Dhruva Sambrani"
date: "Feb 18, 2023"
---

# The world as a calculator

## What is Physics

1. States
2. Dynamics
3. Measurements

## What is Computation

1. Data
2. Functions
3. Output

## They are the same things

Studying one of these is intrinsically related to studying the other.

# Maths for Quantum Computation

## Classical Mechanics - Real numbers

1. Single particle
2. Real numbers - $x$
3. Hamiltonian/Lagrangian/Newtonain Dynamics - $x^\prime = F(x)$
4. Observe with a meter - $M(x)$
5. Multiple objects, repeat numbers

## Classical Mechanics - Probability Distributions

1. Ensembles
2. Probability vectors - $p=\mathbb{R}^n, \sum_{i=1}^{n}p_i = 1$
   1. Vector space over convex combinations over real numbers
   2. Inner product gives overlap
3. Column stochastic matrices - $T = n \times n$ square matrix, $\sum_{j=1}^{n}T_{i,j} = 1, p^\prime = Tp$
4. Observe the system with a meter - $\bar{M}(p)$

## Quantum Mechanics - Complex numbers

1. Single particle
2. Complex numbers as probability amplitudes - $|\psi\rangle=\mathbb{C}^n, \sum_{j=1}^{n} |c_i|^2 = 1$

   1. Vector space over convex combinations over complex numbers
   2. Inner product gives overlap

3. Unitary matrices - $U = n \times n$ square matrix, $U^\dagger U = I_n = UU^\dagger$
   - $|\psi^\dagger\rangle$ = $U |\psi\rangle$

---

4. Measurements

   - Let $P_m$ = $|m \rangle\langle m|$
   - $p(m) = \langle \psi | P_m | \psi \rangle$

5. Multiple particles, tensor product
   - $|\psi_1\rangle \otimes |\psi_2\rangle$
   - $U_1 \otimes U_2$
   - $p(m) = \langle \psi | P_m | \psi \rangle$

## 2 Level systems

$$\cos(\theta) |0\rangle + \sin(\theta) e^{i\phi} |1\rangle$$

- Points on a sphere
- Unitaries are rotations
  - $S_z$, $S_x$, $S_y$
  - $H$, $T$
- CNOT

## Circuit Diagrams

![](./02-18-01-41.png)

- Serial Composition
- Parallel Composition
- Circuit Depth

# Quantum Computers

Quantum Computers are good at simulating unitaries.

The game is to build the correct unitary.

## Linear Search

## Grover Search

1. Oracle
2. Diffusion

