
.. raw:: html

    <div align="left" style="width:300px;height:260px">
        <img src="https://raw.githubusercontent.com/sanshar/Block/master/README_Examples/block_logo.jpg" style="width:300px;height:250px"/>
    </div>

Block: Density Matrix Renormalization Group Algorithms for Quantum Chemistry
============================================================================

**Block 1.5:** (original version) https://github.com/sanshar/Block

**Block 1.5:** (spin-orbit coupling) https://github.com/ElviraRS/Block

**StackBlcok 1.5:** (a faster alternative to the original Block) https://github.com/sanshar/StackBlock

**StackBlcok 1.5:** (stochastic p-DMRG) https://github.com/shengg/stochastic_pDMRG

Documentation: https://sanshar.github.io/Block/

BLOCK implements the density matrix renormalization group (DMRG) algorithm for quantum chemistry. The DMRG is a variational wavefunction method. Compared to other quantum chemical methods, it efficiently describes strong, multi-reference correlation in a large number of active orbitals (occupancies far from 0 or 2). The method is also provably optimal for correlation with a one-dimensional topology, that is, where orbitals are arranged with a chain- or ring-like connectivity. However, with the possible exception of small molecules, for correlation that is dynamic in character, the DMRG may be less computationally efficient than other methods such as coupled cluster theory or multireference configuration interaction. We recommend the use of the DMRG in problems requiring active spaces too large for standard complete active space (CAS) techniques.

**References:**

Chan, Garnet Kin-Lic, and Martin Head-Gordon. "Highly correlated calculations with a polynomial cost algorithm: A study of the density matrix renormalization group." The Journal of chemical physics 116, (2002): 4462-4476. doi:`10.1063/1.1449459 <http://doi.org/10.1063/1.1449459>`_

Chan, Garnet Kin-Lic. "An algorithm for large scale density matrix renormalization group calculations." The Journal of chemical physics 120, (2004): 3172-3178. doi:`10.1063/1.1638734 <https://doi.org/10.1063/1.1638734>`_

Ghosh, Debashree, Johannes Hachmann, Takeshi Yanai, and Garnet Kin-Lic Chan. "Orbital optimization in the density matrix renormalization group, with applications to polyenes and β-carotene." The Journal of chemical physics 128, (2008): 144117. doi:`10.1063/1.2883976 <https://doi.org/10.1063/1.2883976>`_

Sharma, Sandeep, and Garnet Kin-Lic Chan. "Spin-adapted density matrix renormalization group algorithms for quantum chemistry." The Journal of chemical physics 136, (2012): 124121. doi: `10.1063/1.3695642 <https://doi.org/10.1063/1.3695642>`_

Guo, Sheng, Mark A. Watson, Weifeng Hu, Qiming Sun, and Garnet Kin-Lic Chan. "N-electron valence state perturbation theory based on a density matrix renormalization group reference function, with applications to the chromium dimer and a trimer model of poly (p-phenylenevinylene)." Journal of chemical theory and computation 12, no. 4 (2016): 1583-1591. doi: `10.1021/acs.jctc.5b01225 <https://doi.org/10.1021/acs.jctc.5b01225>`_
