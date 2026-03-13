# ATP-NADH-Reaction-Diffusion
A repository for the code I generated used in the paper "Nonlinear contractile response of actomyosin active gels to control signals", published in PRX

The code is well-annotated but non-functional due to dependencies on prior data that has not been uploaded.

"Kymograph_Integration.ipynb" takes experimental data for NADH defluoresence and extracts a 1D measurement of the total NADH consumption along measured values. This code in particular does not have functionality because it requires data not uploaded.

"Strain and Energy v1,0.ipynb" calculates hencky strain and energy consumption from experimental images of a contractile actomyosin mesh network and plots their values in a very large variety of strain measurements, complete with ad-hoc corrections as dictated by the experiment circumstances. Many lines are commented out due to the code being large and time-intensive to run.

"Strain_Div_EnergyCons_Functionalized" and "Localized_Energy_Consumption_Functionalized" are files imported by "Strain and Energy v1,0.ipynb". They have some of the calculations used to calculate strain and energy measurements.

"Nelder-Mead estimates of D and kmy.ipynb" takes experimental data for diffusion and myosin enzyme activity and uses the Nelder-Mead optimization algorithm to find best-fit values for diffusion and myosin activity.

"Fitting Constants Results Plotter_V1,0.ipynb" is a program to run a reaction-diffusion simulation that takes ATP consumption measured in experiment plus simulation and estimates/plots the total energy consumption across space in a 1D line. It pairs particularly with the "Kymograph_Integration.ipynb".

"Reaction-Diffusion lmfit-v14JA.ipynb" is a program that graphs the defluoresence extracted in "Kymograph_Integration.ipynb" from the data, adjusting the myosin enzyme reaction and the diffusion constants in the simulation. 
