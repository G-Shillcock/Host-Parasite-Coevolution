# Host Parasite Coevolution
Information regarding the custom computer code (mathematical algorithms) used in Wild et al.


## System Requirements

Mathematical algorithms require Python 3.6 or higher. Specific libraries required are NumPy 1.19.2, Matplotlib and csv which come by default when one downloads and installs the Python 3.x version of the Anaconda data science toolkit (available for free [here](https://anaconda.org/ "Anaconda's Homepage")). Anaconda supports Windows, Mac and Linux operating systems. Its installation takes around 15 minutes. Algorithms were tested in a Jupyter Notebook with Python 3.8.5.

Some ancillary results were derived in ```cubic_coefficients.mws``` which using the symbolic computer algebra package Maple. This can be purchased [here](https://www.maplesoft.com/pricing/), however please note that often academic institutions have site licenses available to faculty and students free of charge.

All hardware used was typical to a standard desktop or laptop computer.


## Setup

For algorithms used by Wild et al., the user should download ```Host_Parasite_Coevolution.pynb``` and save it to their working directory. The Jupyter notebook explains the analysis behind the best response and morbidity plots (Figures 4 and 5 respectively).


## Demo

To run the demo first open Anaconda Navigator and launch Jupyter Notebook. Navigate to where the ```Host_Parasite_Coevolution.pynb``` file is and open it. In the window that opens find the ```Cell``` tab and click ```Run All```. Alternatively, open an Anaconda prompt and type ```ipython``` to launch an interactive shell. Change directory with the command ```cd path```, where path is the directory where the file is saved. Finally, run the file with the command ```run Host_Parasite_Coevolution.ipynb```.

The Demo takes around 2 minutes to run on a laptop equipt with an Intel Core i9-9980HK CPU and 50GB RAM.


## Instructions for Use

To explore the parameter space further the biological parameters (lines 36-40) can be changed. The table below matches the variable names given in the paper to those found in the code script.

| Code name |  Paper name   | Biological interpretation                                  |
|:---------:|:-------------:|:----------------------------------------------------------:|
|     b     | b<sub>0</sub> | birth rate of infectives in the absence of immune response |
|     u     |       μ       | background mortality rate                                  |
|  nvals/n  |       n       | transmissibility exponent                                  |
| lambdas/l |       λ       | cost to the host to clear the infection                    |
|  vvals/v  |       v       | vertical transmission probability                          |
