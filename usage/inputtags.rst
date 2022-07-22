=========
inputfile
=========

The simulation process is controlled by inputfile. This file should be named a ··input··. 
The most important parameters such as simulation time, MD timestep, functionals ...


Options
=======


Example input file
==================

.. code-block::

	seed 99195510    
	maxcycle 100000  
	box_x  58.0      
	box_y  58.0      
	box_z  58.0      
	pdbfile SOR.pdb  
	functional 0     
	temperature 1580 
	timestep 0.2     
	restart 0        
	updFre 12        
	corrFre 12       
	indist   2.15    
	outdist  2.25    
	qmcores 1
