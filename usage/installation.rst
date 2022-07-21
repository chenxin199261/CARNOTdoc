.. CARNOT documentation master file, created by
   sphinx-quickstart on Thu Mar 31 14:43:15 2022.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

install
==================================


Unzip Package 
>>>>>>>>>


Unzip the source code package, you will see 2 directories (DeFT-source and CARNOT-source). 


Prerequisites Environment
>>>>>>>>>

The following compilers and parallel libraries are needed before compiling CARNOT:

* Fortran compiler  
* C compiler
* MPI library 

Suggested combination: 
 * gcc version 4.8.5 + MPI 5.0 ( intel_mpi/2015_u1) 


Compile Quantum Chemistry Engine
>>>>>>>>>

Enter into the directory of deft-source, and compile the source code of DeFT.

.. code-block:: bash
   make -j 4 

After compilation, a static library name ``libDeFT.a`` is yielded in the directory. Copy this static library to the directory of  CARNOT-source. 

Compile CARNOT
>>>>>>>>>

Enter into the directory of CARNOT-source. And compile the code into executable file ``CARNOT.exe``.


.. code-block:: bash
   make 

