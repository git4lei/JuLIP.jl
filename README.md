# JuLIP: Julia Library for Interatomic Potentials

<!-- [![Build Status](https://travis-ci.org/cortner/JuLIP.jl.svg?branch=master)](https://travis-ci.org/cortner/JuLIP.jl) -->

Julia codes for interatomic potentials and molecular simulations.
Work in progress.

# Installation

JuLIP currently relies on [ASE](https://gitlab.com/ase/ase) and
 [matscipy](https://github.com/libAtoms/matscipy). These should be straightforward
to install from the shell:
```bash
pip install ase
pip install matscipy
```
Afterwards, install JuLIP, from the Julia REPL:
```julia
Pkg.clone("https://github.com/libAtoms/JuLIP.jl.git")
```
And run
```
Pkg.test("JuLIP")
```
to make sure the installation succeeded. Otherwise, open an issue.


# TODO

- [ ] Implement some basic interatomic potentials: Lennard-Jones, Morse, Gupta
- [ ] Implement generic EAM, using data-files
- [ ] Implement an interface for ASE calculators