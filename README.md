# Boundary-conditions
Implementation of boundary conditions for the director orientation

The implementation of the homeotropic boundary condition is universal irrespective of the geometry. 
We use the \patch( ).nf( ) function, which computes the wall-normal vector and prescribes it on the wall.

The wall-parallel boundary condition is more complex and requires a geometry-dependent function.
The code wallPar specifies the wall-parallel boundary condition for a pipe with a symmetry plane 
at z=0, whose pipe axis lies in the x-y plane. Scalars cx and cy denote the x- and y- coordinates 
of the bend axis and the function specified in line 29 computes the appropriate director orientation.



