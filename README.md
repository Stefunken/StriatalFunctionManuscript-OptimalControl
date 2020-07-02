# StriatalFunctionManuscript-OptimalControl

This repository contains: 
- a file .yml to create the "treadmillOC" environment which is necessary to run the codes 
- 3 folders containing useful data (Data_for_fit), results of simulations and model fitting (PickleResults with the 2 subfolders Simulations and Fit), and the figures presented in the paper (FiguresLesionPaper).
- 3 Jupyter Notebooks (described below)

To reproduce the main and supplementary figures of the paper just run the notebook: "Plot_main_fig_lesion_paper.ipynb"
It imports preprocessed data and simulation results and generates the 2 figures of the paper (2 .pdf files are saved in the folder FiguresLesionPaper).

The notebook "Main-OC-Simulations.ipynb" computes all the results related to optimal control simulations and save them in the PickleResults/Simulations folder.

The notebook "Main_fit_alpha_trajectories_bounded.ipynb" loads behavioral data from the Data_for_fit folder, performs the model fitting for the effort sensitivity parameter, and save the results in the PickleResults/Fit folder.


