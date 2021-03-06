![GitHub release (latest by date)](https://img.shields.io/github/v/release/Geo-Linux-Calculations/gnu-gama-g3)
![GitHub Release Date](https://img.shields.io/github/release-date/Geo-Linux-Calculations/gnu-gama-g3)
![GitHub repo size](https://img.shields.io/github/repo-size/Geo-Linux-Calculations/gnu-gama-g3)
![GitHub all releases](https://img.shields.io/github/downloads/Geo-Linux-Calculations/gnu-gama-g3/total)
![GitHub](https://img.shields.io/github/license/Geo-Linux-Calculations/gnu-gama-g3)

# GNU Gama G3

GNU package Gama is a C++ free software for geodesy released under GNU
General Public Licence. Project Gama was started in 1998, in 2001 was
dubbed a GNU packaqe and today contains the following main components:

### gamalib

C++ class library for handling geodetic observations
(measurements) and points (coordinates), computation of
approximate coordinates (needed for linearization) and adjustment
of local geodetic networks in 3d.  C API to essential gamalib C++
classes and functions is also available. Numerical solution of
adjustment is based on orthogonal decomposition of the design
matrix (ie without "normal equations"); currently supported
algorithms are SVD and GSO (an algorithm based on Gram-Schmidt
orthogonalisation). Adjustment on the ellipsoid is a long term
goal.

### program gama-local

C++ program for adjustment of horizontal
geodetic network based on gamalib (also available as a public
service accessible by email); format of input data is defined in
XML. Data structures used in adjustment enable usage of general
variance-covariance matrices of observations and are designed to
enable implementation of sparse matrices in future versions.

### matvec
C++ matrix/vector template classes used in adjustment
computations in gamalib.

### rocinante
is a GUI for GNU Gama based on Qt graphical library
that is available for GNU/Linux under GNU GPL. Rocinante binaries 
are also available for win32 platform; see 
* http://roci.sourceforge.net/  
for more information.

More information on GNU GaMa can be found at
* http://www.gnu.org/software/gama
