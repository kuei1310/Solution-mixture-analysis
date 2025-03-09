#  Solution-Mixture-Analysis
This repository contains analysis scripts related to the methods described in our recent paper. The provided codes facilitate the analysis of polymer bulk structures and solution-phase behavior.

##  Project Structure
-  ```Analysis_and_run/```: Contains all analysis scripts.
-  ```bulk/```: Includes an example of bulk structure analysis using the P-SO2 polymer bulk system.
-  ```solution/```: Provides three polymer solution systems as examples for solution-phase analysis.
-  ```trajectory/```: Contains the trajectory files for the **NPT** simulation of the P-2O polymer solution

##  Analysis scripts
###  1. Density Profile Analysis (```density_profile.ipynb```)
-  Reads the **tpr** and **gro** files of the solution structure.
-  Computes the density profile of **polymer, AA, NMP, and water**.
-  Determines the interface position based on the density distribution.
###  2.  $\pi-\pi$ Stacking Analysis (```pi-pi-stacking.ipynb)
-  Reads the bulk structure data (```bulk.tpr``` and ```bulk_pbc.gro```)
-  Analyzes the number of **$\pi-\pi$ stacking interactioins** and classifies them into different stacking types.
-  Generates the **backbone structure** for validation of atom selection groups. (```backbone.gro```)
-  Outputs a **gro file** containing the identified $\pi-\pi$ stacking structures. (```PSO2-pipi.gro```)
-  Saves the stacking classification results in a **text file** for further analysis. (```PSO2-pipi.txt```)
