# Article repository
"Title".

Available online: -
doi: --

Required: python 3.8; tensorflow 2.4.1; RDkit 2021.03; 
The code is in Jupyter Notebook/Jupyter lab format for more convenient prototyping, Anaconda environment is recommended.
GPU with support for CUDA 10.1 is recommended

The full dataset can be used with or without the solvents that preceed the crystallization step, depending on what columns are pre-processed before the training. "RP" column denotes the compounds in SMILES format, "Solvent" column - solvents used for the crystallization process, "Pre_sol" - solvents that are in the mixture before the crystallization step. Note: one instance mey have multiple solvents, therefore they are separated by the bar "|" character. Autoencoders can be downloaded [here](https://vduedu-my.sharepoint.com/:f:/g/personal/mantas_vaskevicius_vdu_lt/EpwAcKyv3w1ClxBjw7x-wpEBV4Cboj6KehQSesMBuLYLvg?e=rhTwdN).
