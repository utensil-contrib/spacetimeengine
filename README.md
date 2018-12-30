# spacetime-toolkit
A python toolkit for exploring the Einstein's field equations. This toolkit gives the user the ability to completely analyze any metric you feed to it.

<img src="https://latex.codecogs.com/gif.latex?O_t=\text { Onset event at time bin } t " /> 

How to use?
===========
Currently this project is in a state of development, however the core functionality appears stable and has passed each test. To demonstrate this software just run

$ python example.py

In the example you can see various spacetimes which are a primary argument.

    coordinate_set = [ x0, x1, x2, x3 ]
    mt = Metric(reissner_nordstrom_spacetime, coordinate_set)

To change the metric just swap it out for another one or build your own. Sympy appears quite rhobust!

Project Goals
=============

1.) For a given metric tensor and coordinate set, provide functions which compute all of the following quantities:
    Connection Coefficients
    Ricci tensor, 
    Ricci scalar, 
    Einstien tensor,
    Stress Tensor,
    Geodesic equations,
    Plotting velocities, orbits, geodesic paths.
    
2.) Print the previous terms in a clean and intuitive predefined format which bypasses the limitations imposed by sympy.

3.) Computing all geodesics equations for a given metric, coordinate set, parameterization type and initial conditions.

4.) Plotting any or all acceleration vectors, velocity vectors, position vectors for any or all spacelike,timelike and null geodesics.

5.) Provide visualization tools which can be configured to match any metric.

6.) Provide a configuration file which allows the user to customize the output profile for a given metric and coordinate set.

Project Purpose
===============
 1.) To provide code which demonstrates general relativity and can be studied.
 2.) To provide code which can be utalized by researchers or engineers.
 3.) To provide concrete numeric calculations directly from the symbolic form of the einstien field equations.
 4.) Provide context by integrating latex representations of the functions.

TODOs
=====
So much.. 

Timeline
========
Jan - Einstiens Field Equation + Geodesics
Feb - Plotting trajectories
Mar - Config file customizations.
