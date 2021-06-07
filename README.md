# QuantumQueue
Contents:
1. Scripts to capture data
2. Scripts to generate graphs
3. Data

How to run:
1. Though we used Qiskit to collect information from the IBM machines (through our access to the machines) Qiskit is not required to run the Queue_graphs.ipynb which generates most of the graphs in the paper. The data is stored in the csv files.
2. Qiskit is required to run the other notebooks (mainly focused on compilation data) and can be installed from https://qiskit.org/documentation/getting_started.html
3. The use of JupyterLab is ideal since the provided scripts are in the form of jupyter notebooks
4. All the collected metadata from two years of quantum runs are provided in the csv files but they do not have to be accessed manually
5. It is sufficient to run the notebook: Queue_graphs.ipynb, to produce most of the paper's results
6. The notebook can be executed by running each block in the notebook one after the other.
7. Graph results will be automatically produced.
8. Secondary compilation data can be generated via the Measure-compile* notebooks.
