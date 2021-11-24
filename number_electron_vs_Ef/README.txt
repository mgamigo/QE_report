The 'efermig.f90' is a modification of QE's version to print out the number of electrons as a function of the chemical potential and other quantities.
You can replace this file in your QE folder ('PW/src')

After compiling with the new subroutine, you can run the test calculation with

pw.x < 0.0.pwi > out

Then use the jupyter notebook 'plot.ipynb' to plot the result.
