# Gantry-table_collision
Creation of safe space to avoid any gantry collision during RT treatment.

Using "A practical method for predicting patient-specific collision in radiotherapy" by Miao et al. (DOI: 10.1002/acm2.12915).
This repository contains the general code to create a so-called safe-space, where collisions don't happen. This will correspond to cylinder.
The origin of the coordinate system will be equal to the treatment isocenter, allowing to take any table shifts into account.
The radius of the cylinder corresponds to the distance between the treatment isocenter and the most external part of the treatment head (touchguard). 
