<div align="center">

# 𝑸𝒖𝒂𝒏𝒕𝒂

### *Notes, Formalism & Problem Sets in Quantum Mechanics*

```
∂Ψ            ℏ²
iℏ ── = − ──── ∇²Ψ + VΨ
∂t           2m
```

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Made with LaTeX](https://img.shields.io/badge/Made%20with-LaTeX-008080.svg)](https://www.latex-project.org/)
[![Field](https://img.shields.io/badge/Field-Quantum%20Mechanics-6a0dad.svg)]()
[![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)]()

</div>

---

## §0 &nbsp;Abstract

**quanta** is a growing collection of typeset notes and derivations spanning the standard first course in quantum mechanics — from the wave function and the Schrödinger equation through formalism, three-dimensional systems, and identical particles. Every document is compiled from LaTeX source into a clean, citation-ready PDF.

---

## §1 &nbsp;Table of Contents

| §   | Document | Description |
|:---:|:---------|:-------------|
| 1.1 | [`wave_function.pdf`](./wave_function.pdf) | The wave function Ψ, the Schrödinger equation, statistical interpretation, probability current, and the uncertainty principle $\sigma_x \sigma_p \ge \hbar/2$ |
| 1.2 | [`time_ind_schro_eqn.pdf`](./time_ind_schro_eqn.pdf) | Stationary states, separation of variables, boundary conditions; square wells, free particles, δ-function potentials, and the harmonic oscillator (ladder operators + Hermite polynomials) |
| 1.3 | [`formalism.pdf`](./formalism.pdf) | Hilbert space, Dirac (bra–ket) notation, Hermitian operators, eigenvalues/eigenfunctions, and the generalized uncertainty principle |
| 1.4 | [`qm_3D.pdf`](./qm_3D.pdf) | Spherical coordinates, angular equation & spherical harmonics, radial equation, the hydrogen atom, and spin ($\sigma_x, \sigma_y, \sigma_z$, Stern–Gerlach) |
| 1.5 | [`identical_parc.pdf`](./identical_parc.pdf) | Two-particle systems, symmetric/antisymmetric wave functions, the Pauli exclusion principle, bosons vs. fermions |

---

## §2 &nbsp;Syllabus

### 2.1 &nbsp;The Wave Function
- The Schrödinger equation and statistical interpretation
- Probability currents & conservation of normalization
- The uncertainty principle, from first principles of wave behavior

### 2.2 &nbsp;The Time-Independent Schrödinger Equation
- Stationary states via separation of variables
- Classic potentials: infinite well · finite well · free particle (wave packets, phase/group velocity) · δ-function
- The quantum harmonic oscillator — algebraic method ($a_\pm$) and analytic method (power series / Hermite polynomials)

### 2.3 &nbsp;Formalism
- Hilbert space and Dirac notation
- Hermitian operators, eigenvalues, eigenfunctions
- Generalized statistical interpretation & generalized uncertainty principle

### 2.4 &nbsp;Quantum Mechanics in Three Dimensions
- Spherical coordinates: angular equation (spherical harmonics) + radial equation
- The hydrogen atom — energy levels, orbital angular momentum, radial wave functions
- Spin angular momentum, Pauli matrices, Stern–Gerlach

### 2.5 &nbsp;Identical Particles
- Two-particle systems and (anti)symmetrized states
- The Pauli exclusion principle
- Bosons vs. fermions; a first look at atoms, solids, and statistical mechanics

---

## §3 &nbsp;Building from Source

If source `.tex` files are added alongside the compiled PDFs, they can be built with any standard distribution:

```bash
git clone https://github.com/rafidabruhr/quanta.git
cd quanta
pdflatex wave_function.tex
```

Recommended packages: `amsmath`, `amssymb`, `physics`, `braket`, `tikz`.

---

## §4 &nbsp;Reference

Primarily structured around the canonical treatment in:

> D. J. Griffiths & D. F. Schroeter, *Introduction to Quantum Mechanics*, 3rd ed., Cambridge University Press.

---

## §5 &nbsp;License

Distributed under the **MIT License**. See [`LICENSE`](./LICENSE) for details.

<div align="center">

---

*"Anyone who is not shocked by quantum theory has not understood it."* — N. Bohr

</div>
