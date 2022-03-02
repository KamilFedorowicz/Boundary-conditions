# Boundary-conditions
Implementation of boundary conditions for the director orientation

The implementation of the homeotropic boundary condition is universal irrespective of the geometry. 
We use the \patch( ).nf( ) function, which computes the wall-normal vector and prescribes it on the wall.

The wall-parallel boundary condition in the bend is more complex and requires a dedicated code,
which is given in the file wallPar.

