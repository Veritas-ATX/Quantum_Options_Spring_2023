# Quantum_Options_Spring_2023
This is a repository intended to store code artifacts related to my research project in using quantum computers to value financial options. Each of these files was ran in the IBM Quantum Lab to ensure Qiskit related packages were properly setup. They can be ran on a local machine provided the installs are performed correctly.

The files contained in this repository are as follows: 
- Options_Demo.ipynb: Jupyter Notebook with my presentation given on 5-5-23 about my intial efforts to price lookback options
  - Contains the explanatory code for loading probability distributions into quantum circuits
- Classical_Lookback.ipynb: Jupyter Notebook containing code to run Monte Carlo simulations for call and put lookback options
  - Currently setup with parameters identical to that of the quantum version code for ease of comparison
- Quantum_Lookback_Call.ipynb: Jupyter Notebook containing code to run quantum simulations for call lookback options
  - Note that this file contains more explanatory comments than the quantum put
- Quantum_Lookback_Put.ipynb: Jupyter Notebook containing code to run quantum simulations for put lookback options
