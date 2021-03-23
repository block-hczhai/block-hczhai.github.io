
ZMPO-DMRG: A Parallel Fock-Space ab DMRG code based on MPO for Quantum Chemistry Hamiltonian
============================================================================================

**Package:** https://github.com/zhendongli2008/zmpo_dmrg

Basic ideas:

1. The central quantity is the three indexed operators in MPO format.

2. Parallelization is achieved at the operator level.

Supports:

1. Ab inito DMRG with/without particle number and Sz symmetry

2. Spin-projected DMRG with S^2 symmetry

3. Conversion form spin-projected MPS to spin-adapted MPS used in the BLOCK code [for examples, see source/samps/example_conversion/]

**Reference:** Li, Zhendong, and Garnet Kin-Lic Chan. "Spin-projected matrix product states: Versatile tool for strongly correlated systems." Journal of chemical theory and computation 13, no. 6 (2017): 2681-2695. doi:`10.1021/acs.jctc.7b00270 <https://doi.org/10.1021/acs.jctc.7b00270>`_
