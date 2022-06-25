# RK4_Propagator

Propagates an orbit around the Earth using an RK4 Approximation. To download on your own computer, go to https://pypi.org/project/RK4-Propagator/. It can be imported from Python with 'from RK4_Propagator import RK4_Propagator'. 

The package contains the function RK4_Propagator(start, end, N, u0) where start and end are the start and end times, N is the number of timesteps, and u0 is an array of six values that represent the initial conditions (x, y, z, dx, dy, dz) of the satellite. The function returns an array of N+1 timesteps where the first value in the array has the start conditions and the last element in the array has the final conditions.
