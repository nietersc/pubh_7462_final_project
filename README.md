# pubh_7462_final_project
Final project for PUBH 7462 (Spring 2025)

1) Author: Chris Nieters
2) Name of product: Spectroradiometer Data Explorer Shiny App or R package
3) Product type: Shiny App or R package
4) Product purpose:To provide easy conversions and calculations for spectroradiometer data that researchers and plant producers need to accurately characterize their lighting conditions for experiments or production environments
5) Data sources: publically available ASTM G173-03 Reference Spectra (SMARTS v. 2.9.2) and example LED spectrum will be provided from a commonly used blue and red light fixture
6) Product features: Watts/m^2 to umol/m^2/s conversion, calculation of full-width half-max of an emission source, color fraction calculator, photon flux density calculator, daily light integral calculator
7) Automation [if applicable]: not applicable
8) Interactivity [if applicable]: users will be able to apply these conversions and calculations to their spectroradiometer data
9) Parallelization [if applicable]: not applicable
10) Programming challenges: it will be challenging to work with data structures from different spectrometers or if users have multiple readings in a single .csv or a folder to map through multiple readlings simultaneously. Making these functions and calculators modular will take a lot of thought and warning messages. If I opt to make an R package, it will be challenging to get all the documentation correct - if I do a Shiny app
11) Division of labor: me :)