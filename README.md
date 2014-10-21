Neutralizing background charge correction for VASP.5.3.5
==========================================

**Authors:** Kiran Mathew and Richard Hennig

http://theory.mse.cornell.edu/

PREREQUISITES
=============
[VASP](http://www.vasp.at/) version 5.3.5.

Compiler and library requirements are the same as that of VASP ([vasp wiki] (http://cms.mpi.univie.ac.at/wiki/index.php/Installing_VASP))

INSTALL
========

- Apply the interface patch to the original VASP source code.
```   
    cd <VASP src directory>
    patch -p1 < <path to the interface patch file>
```
- ``` make clean ```
- ``` make ```
