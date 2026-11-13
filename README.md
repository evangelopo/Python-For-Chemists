# Python-For-Chemists
[![Project Status: Active](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)
[![License: CC-BY 4.0](https://img.shields.io/badge/License-CC--BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

Python-For-Chemists is a collection of learning material for an introductory Python course for undergraduate chemistry students.


| Notebook | Open |
|---|---|
| 1. Coding basics | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/evangelopo/Python-For-Chemists/blob/main/notebooks/01_coding_basics.ipynb) |
| 2. Variables | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/evangelopo/Python-For-Chemists/blob/main/notebooks/02_variables.ipynb) |
| 3. Variables II | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/evangelopo/Python-For-Chemists/blob/main/notebooks/02_variables_II.ipynb) |
| 4. Loops | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/evangelopo/Python-For-Chemists/blob/main/notebooks/03_loops.ipynb) |
| 5. Functions | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/evangelopo/Python-For-Chemists/blob/main/notebooks/04_functions.ipynb) |
| 6. Functions II | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/evangelopo/Python-For-Chemists/blob/main/notebooks/04_functions_II.ipynb) |


## Dependencies and Installation

This project uses the Python programming language, and requires Python >= 3.9.

Units will require different packages from the scientific Python ecosystem. The easiest way to install dependencies is using the Anaconda distribution, otherwise the [requirements.txt](requirements.txt) file also summarises the needed packages. 

If you just want to get started with the Units use the links to the CoLab notebooks provided. Otherwise you can follow these steps to get your local environment setup:

1. Get your anaconda distribution setup. See [here](https://datacarpentry.org/2016-05-29-PyCon/install.html) for detailed instructions.
2. Open a terminal or anaconda promt.
2. Create an environment using the following command
	
	```
	conda create -n ddc python=3.9
	```
	
3. Activate the environment and install the required packages into it:
	
	``` 
	conda activate ddc
	conda install jupyter pandas scipy nglview==3.0.3 ipywidgets==7.6.0 pint mendeleev vpython matplotlib jupyter-server==1.23.6
	```
	
4. Now you can start your Jupyter notebooks as:
	
	```
	jupyter notebook Unit_01/Unit_01_problem_solving_I.ipynb
	```

## License

These materials are made freely available, and are licensed under a [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.