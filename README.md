# Repressilator Gene Regulatory Network Simulation
This project focuses on exploring the behavior of the Repressilator gene regulatory network using in silico modelling for a university assignment. The simulation is implemented in a Jupyter Notebook using the Python programming language. The project consists of a single notebook that combines all six tasks into one for convenience.

## Project Strucuture
The project is organised as follows:
1. **papers**/folder
   * This folder contains relevant literature for the project, providing relevant background information.

2. **report**/folder
   * This folder contains the report produced as part of the project. It summarises the finding, methodology, and conclusions drawn from the simulations

3. **code**/folder
   * This folder contains the Jupyter Notebook file named `Repressilator_Simulation.ipynb`. It combines all six tasks into a single notebook for easier access and readability. Please be aware that some figures have been shown multiple times in the notebook, to produce a figure that is
appropriate for the report.

## Tasks Covered in the Notebook
The notebook covers the following tasks related to simulating the Repressilator gene regulatory network:
1. **Task 1:** Exploring the behaviour of the cooperative reaction kinteics used to model repression
2. **Task 2:** Simulating the Repressilator using a deterministic ODE model
3. **Task 3:** Investigating the dependence of oscillatory behaviour on parameters
4. **Task 4:** Adding a GFP reporter to the model
5. **Task 5:** Controlling the model behaviour using an inducer and increased translation
6. **Task 6:** Simulating the Repressilator using a stochastic model and analysing multiple runs

## Running the Notebook
To reproduce the results and findings from the project, follow these steps:
1. Install Python 3.10 and Jupyter Notebook on your machine if you havent already.
2. Close or download the project repository
3. Navigate to the **code**/folder and open the Jupyter Notebook file named `Repressilator_Simulation.ipynb`
4. Run the notebook by executing all the cells. Ensure that the required modules and variables are imported in the first cell of the notebook.
5. The notebook contains code, explanations and visualisations to guide you through the simulation process and analysis. Each task is clearly labelled. Make sure to run each task in its entirety to obtain the complete results and repliate the report. You can modify the code or parameters to experiment with different scenarios and observe their effects.

## Dependencies
The project relies on the following Python libraries and modules:
* NumPy
* SciPy
* Matplotlib

You can install the necessary dependencies using `pip`:

```bash
pip install numpy scipy matplotlib
