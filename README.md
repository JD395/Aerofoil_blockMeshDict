# Jay Darji Meshing template for aerofoil
# Aerofoil_blockMeshDict
Meshing of NACA0012 using blockMeshDict utility provided by OpenFOAM. 
The mesh is generated using 12 blocks, which can be described as 6 inner blocks and 6 outer blocks.
Some things are to be done manually. The points for interpolation to create 4 splines, which makes the aerofoil as well as 4 splines which creates the outer block are to be taken as per your choice.
Then take points in between say at 50% or 25% of chord length and put their values in xp11, xp14 etc. 
