# Stratospheric perturbation lifetime
In high-speed aircraft scenarios the aircraft emit at stratospheric altitudes. In the stratosphere emitted trace gases are transported and chemically converted throughout the middle atmosphere. The resulting perturbation lifetimes are a measure of transport from the altitude of emission to the troposphere. Few processes exist in the middle atmosphere, that remove emitted trace gases and other perturbed trace gases. Examples are dehydration and denitrification in polar stratospheric clouds. Hence, most perturbed trace gases are transported to the troposphere and eventually removed by sedimentation and other processes in the troposphere. 

# Applications
This repository provides code for the following applications
- To calculate perturbation lifetimes
- To estimate perturbation lifetimes using interpolation and extrapolation at all stratospheric altitudes
- To calculate a correction factor s. s is used to speed up model simulations with stratospheric aircraft perturbations.

# Limitations
The input is based on perturbation lifetimes from Grewe & Stenke (2008) and Pletzer et al (2022, under review). The perturbation lifetimes come with the assumption, that perturbations have very low lifetimes at tropospheric altitudes and are removed very fast compared to stratospheric altitudes. 

# Python environment requirements
The software requires various functions from the following python modules:

- numpy
- scipy
- matplotlib

Install the required packages with `pip install numpy scipy matplotlib`.
