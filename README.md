# Host Parasite Coevolution
Information regarding the custom computer code (mathematical algorithms) used in Shillcock et al 2022.


## System Requirements

Mathematical algorithms require Python 3.6 or higher. Specific libraries required are NumPy 1.19.2, Matplotlib, Scipy, itertools and csv. These come by default when one downloads and installs the Python 3.x version of the Anaconda data science toolkit (available for free [here](https://anaconda.org/ "Anaconda's Homepage")). Anaconda supports Windows, Mac and Linux operating systems. Its installation takes around 15 minutes. Algorithms were tested in Google Colab Notebook with Python 3.8.5.

Some ancillary algebra was done in [Host_Fitness.mw](https://github.com/G-Shillcock/Host-Parasite-Coevolution/blob/94076fb928d4864fbb5c4c3910b6cd8fd1a4fa52/Host_Fitness.mw) and [cubic_coefficients.mws](https://github.com/G-Shillcock/Host-Parasite-Coevolution/blob/94076fb928d4864fbb5c4c3910b6cd8fd1a4fa52/cubic_coefficients.mws), which using the symbolic computer algebra package Maple. This can be purchased [here](https://www.maplesoft.com/pricing/), however please note that often academic institutions have site licenses available to faculty and students free of charge.

All hardware used was typical to a standard desktop or laptop computer.


## Python Setup

For algorithms used by Shillcock et al., the user should download this repository using the green ```Code``` button located in the top right. The python notebook [Shillcock_et_al.ipynb](https://github.com/G-Shillcock/Host-Parasite-Coevolution/blob/94076fb928d4864fbb5c4c3910b6cd8fd1a4fa52/Shillcock_et_al.ipynb) can then be extracted and saved to your working directory.


## Python Demo

To run the demo first open Anaconda Navigator and launch Jupyter Notebook, navigate to where Shillcock_et_al.ipynb is saved, and open it. In the window that opens find the ```Cell``` tab and click ```Run All```. Alternatively, open an Anaconda prompt and type ```ipython``` to launch an interactive shell. Change directory with the command ```cd path```, where path is the directory where the file is saved. Finally, run the file with the command ```run Shillcock_et_al.ipynb```.

The Demo takes around 1 minutes to run on a laptop equipt with an Intel Core i9-9980HK CPU and 50GB RAM.

Instructions on how to save all generated data are includes in the python notebook.
