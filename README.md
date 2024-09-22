# qml-business-applications

This repository contains the practical implementation work associated with my Master Thesis "Business Applications of Quantum Machine Learning" for the Master Program in Digital Economy at Vienna University of Economics and Business. As part of the thesis, the notebooks in this repository demonstrate how to analyze two proxy cases represented by publicly available datasets on churn prediction and predictive maintenance with variational QML methods provided by the PennyLane and Qiskit Machine Learning frameworks.

## Contents:
- Full text of Master Thesis: MA_Business_Applications_of_QML.pdf
- Datasets: bank_churn_prediction.csv, predictive_maintenance.csv
- Jupyter Notebooks: churn_pennylane.ipynb, predictive_maintenance_qiskit_ml.ipynb
- Anaconda Environment Specification: qml_env.yml

## Running the code:
Both cases were run using a local installation of Anaconda on a Windows 11 64bit machine. To replicate the results, you can set up the exact environment used by installing Anaconda or Miniconda (significantly smaller overhead, but command-line only) and create the environment from the attached yml file. To this end, run the command: \
\
conda env create -f qml_env.yml

Then activate the environment and start Jupyter Lab as follows: \
conda activate qml_env \
jupyter lab

Then navigate to the directory where you stored this project folder using the Jupyter interface.
