# Race-Car-Aerodynamics
SolidWorks, a three dimensional computational fluid diagram simulation software tool, was first used to understand drag and lift forces on the race car through geometric modelling of an air foil by importing coordinates.

Next, a basic airfoil structure was imported into SolidWorks and the 2D depiction was translated into a 3D model through utilization of available functionalities and options within the software environment.

SimScale, a cloud-based simulation platform, was then used to perform advanced simulations like computational fluid dynamics (CFD) through importation of the previously constructed airfoil into the platform.

A mesh of dimensions 0.5x0.3x0.25 m was created around the 0.1 m imported airfoil. The velocity inlet Ux  was allocated value of 25m/s with the face fronting the leading the edge of the airfoil chosen as assigned face. Similarly, a pressure outlet was created on the opposite face with ‘Fixed value’ as pressure type. Moreover, symmetry was attributed to the face left to the airfoil. A no-slip wall was created on the face under the airfoil and named ‘floor’. Lastly, a slip wall was created on the remaining two faces. Lift direction ly was then adjusted to 1 m and the same procedure was applied to drag value dx with all air foil faces set as assigned faces.

Lastly, the simulation was set to run and the force plots, specifically the pressure force in y and viscous force in x, were studied and interpreted to come to a conclusion.


