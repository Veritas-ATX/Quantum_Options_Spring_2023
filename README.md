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

To run these files using IBM Quantum Lab in a browser, create an IMBid and follow the tutorial at this site: https://quantum-computing.ibm.com/lab/docs/iql/

Once you have set up your own first notebook, you can then download the files from this project and then upload to your files in the Quantum Lab. The interface should be familiar to anyone with experience using Jupter Lab or Google Colab. You should not need to install additional packages anc can simply run all cells in the provided notebook as soon as they are uploaded.

In order to run these files locally, follow the below commands to set up a python environment with the correct dependencies. Note that these commands work for MacOS and presume the user has python, conda, and git pre-configured.

```console
git clone https://github.com/Veritas-ATX/Quantum_Options_Spring_2023.git
cd Quantum_Options_Spring_2023
conda create -n myenv python=3.10
conda activate myenv
pip install numpy scipy tqdm matplotlib jupyterlab 'qiskit[visualizaton]'
pip install qiskit-finance
```
