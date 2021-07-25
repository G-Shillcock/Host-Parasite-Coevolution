# Host Parasite Coevolution
Information regarding the custom computer code (mathematical algorithms) used in Wild et al.

## System Requirements

Mathematical algorithms require Python, version 3.6 or higher. Specific libraries required are NumPy, Matplotlib and csv. Algorithms were tested in a Jupyter Notebook with Python 3.8.5. All hardware used was typical to a standard desktop or laptop computer.

## Installation Guide

For algorithms used by Wild et al., the user should download the following files and save them to their working directory:

TwohostOnepopODE.m 

This function returns the right-hand side of one-population version of the dynamic model described in Note 1 of the Supplementary. The output of the function is passed to Matlab's built-in differential-equations solver, "ode45." The function allows one to ultimately identify the equilibrium around which the invasion analysis in Note 2 of the Supplementary is based.

All input required is captured by comments in the script itself.

## Demo

The file SupplementaryCode7.m is demo that creates figures found in the Supplementary Information file. Make sure SupplementaryCode7.m is saved to the same directory in which you find the six files described in previous section. To run the demo open the SupplementaryCode7.m file and click the green "Run" arrow found in the top menu bar of the Editor window. Alternatively, navigate to the working directory type SupplementaryCode7" at the Matlab prompt that appears in the Command Window. Note that you may be prompted by Matlab to add your working directory to its search path; if this happens, choose the "Add to path" option.

The Demo takes 470.5 sec (about 8 min) to run on a laptop equipped with an Intel Core i7-7600U CPU and 16GB RAM.


## Instructions for Use

Figures in the main text containing numerical results can be reproduced using the data supplied along with the Python scripts provided. The Python scripts rely on the numpy, matplotlib, pandas libraries. These libraries come, by default, when one downloads and installs the Python 3.x version of the Anaconda data science toolkit (available for free at anaconda.org). In order to produce figures, the Python script and corresponding data file must be found in the same working directory.

The data used in FIGURE 4 can be found in Fig\_4\_Sept\_13\_2019.csv. The file header contains information about model settings used. Column headings make reference to the full constrained model ("FC" prefix) and the origin-specific model ("HO" prefix). In the former case, pathogens are constrained to use a single alpha strategy regardless of host encountered (the "benchmark" referred to in the main text). In the latter case, pathogens can condition alpha on the sex of the host from which their current infection orginated. Column headings with the "aij" suffix refer to alpha\_ij where i,j = 1,2 (1=female and 2=male). Column headings with the "bijk" suffix refer to beta\_ijk where i,j,k = 1,2. The relevant Python script is SupplementaryCode8.py and it can be run by opening the file in an IDE (e.g. the Spyder IDE that comes with Anaconda) and pressing the green triangle button on the menu bar (alternatively, press Function Key 5).
