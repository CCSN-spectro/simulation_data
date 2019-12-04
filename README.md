# simulation_data content

- "fits_data"
A-A_fits_data_g2.dat
A-A_fits_data_g3.dat
CoCo_fits_data_g2.dat
CoCo_fits_data_g3.dat

Results from 25 1D simulations.
Contain the results of the "best fit" data for g2 and g3 modes.
The file format is: x,f
The fitting function is f=a+bx+c^2+dx^3

where
f is the frequency in Hz
x = M/R**2 for g2 mode
and
x = sqrt(M/R**2)p_c/rho_c**2.5 for g3 mode

- "true data"
s20_data_g2.dat
s20_data_g3.dat

Contain the 'true' data i.e. the time evolution of x (the same x than in the fits)
for g2/g3 for the s20 model. These data comes from a 2D simulation.

