# Small_Office_Prototype_Energyplus_Model

This repository contains the EnergyPlus Input Data File (IDF) and associated weather file used in the simulations of a small office commercial prototype building, as described in our research paper. 

Contents:
-**SmallOffice_IDF.idf:** This IDF file models a small office building modified for our specific research needs. Modifications include reduced window and door sizes to explore their effects on building energy performance and thermal comfort.
-**Weather_File.epw:** The weather file used for the simulations, providing environmental conditions that closely mimic the specific geographic location of our study.

Simulation Setup:
The simulations are designed to study the impact of door opening factors (DOF) and window opening factors (WOF) on the building's thermal dynamics. The DOF was varied from 0% (completely closed) to 100% (fully open) in 25% increments, while the WOF was tested from 0% to 10% in 2.5% increments. The aim was to observe the changes in thermal interactions between different zones of the building.

How to Run Simulations:
-**Install EnergyPlus:** Ensure that you have the  version 9.6 of EnergyPlus installed on your system.
-**Download the Files:** Clone or download the IDF and EPW files from this repository.
-**Run the Simulation:** Open the EnergyPlus simulation environment, load the IDF file along with the EPW file, and execute the simulation.


Reference:
For more details about the simulation setup, modifications, and analysis, our published manuscript titled "[Modeling the Impact of Passive Ventilation Systems on Multi-Zone Thermal Dynamics]" 

