# Radon_Detector: Alpha-decay radiation lowers its energy by passing throught a medium (air in this case) and after a certain distance (depending on the emitting source)
# it is no longer detectable, the energy of the alpha particle is not able to trigger the detector. It is important to consider the geometry and this distance.

Python code for estimation of efficiency of a radon detector. It considers not only geometry but also the radiation length.
The "RadonDetectorFunctions" archive contains the functions for:
- Creating geometry of detector
- Creating the spatial grid of points in a XZ plane
- Creating a grid in spherical coordinates (for each point) for directions
- Counting rays that reach the detection surface in a distance lower to the distance where the rays are not longer detectable
- Plotting the efficiency sourfaces

Future Work:
- Add function of energy deposition by alpha-radiation
- Add Bethebloch equation for energy stimation
- Add Electric Field and Solve the PDE of electromagnetic Field
- Add function for the position of daughters (decay products) within an electric-field 
