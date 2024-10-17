## Tutorial for BaNDyT: Bayesian Network Analysis of Dynamic Trajectories

A series of tutorials for the application of BaNDyT: Bayesian Network analisis of Molecular Dynamic simulation trajectories. 

The python module can be requested by email from: Sergio Branciamore (sbranciamore@coh.org) or Andrei Rodin (arodin@coh.org).

This tutorial was prepared and released along with the publication: <insert link to publication here>

**Installing Requirements**

Following Python packages are required: numpy,pandas,seaborn,matplotlib,pydot,igraph.
We recommend using pip to install them on your local machine:

```pip install numpy
pip install pandas
pip install seaborn
pip install matplotlib
pip install pydot
pip install igraph
```

**Installation**

No particular installation procedure is necessary. However to enable faster compute routines compilation of cpp source in the folder containing this project
is necessary. The folder contains Makefile that will tell the compiler what to do as long as 'make' utility and g++ compiler are present.

In the BaNDyT folder execute following commands:

```bash
touch ofext.cpp
make
```
This procedure should update C++ extension to the current architechture and make
optimized routines available.

**Workflow Example**

The example for single residue-based approach of analysis of MD trajectories was provided in:
*BaNDyT-single-residue-based-approach-tutorial.ipynb
