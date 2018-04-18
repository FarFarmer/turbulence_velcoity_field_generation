# turbulence_velcoity_field_generation

v_generate_shapeXYZ.py:

Python code that generates 3D velocity field on grid of shape (NX, NY, NZ), that has a Gaussian pdf, and a given (Kolmogorov-like) power spectrum E(k) with specified normalisation sigma_V and k_max

Note: with both solenoidal and compressive components! For true 3D field (i.e. all NX, NY, NZ >> 1), the solenoidal component has 2 times power than the compressive components, as expected for random velocity fields. For decomposing a field to solenoidal and compressive components, see the 'helmholtz' repository.

v0_xyz_100_400_2.dat:

example of generated data 
