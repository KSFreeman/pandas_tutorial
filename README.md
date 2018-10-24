# Pandas Tutorial

This repository contains an input data file, a jupyter notebook that is missing part of the code to process the file, and a folder with the desired output. Follow the instructions below to install everything you need beforehand, then we will go through the notebook together and fill in the missing code. If you already have python 3 and the packages jupyter, pandas, and numpy installed you are ready and can skip the directions below. 

## Python installation instructions

1) Download anaconda (3.7 version\*)

	[https://www.anaconda.com/download/](https://www.anaconda.com/download/)

	If your hard drive space is limited, you might want to install minconda instead:

	[https://conda.io/miniconda.html](https://conda.io/miniconda.html)

	With miniconda, you manually install the packages you want. Anaconda comes pre-loaded with lots of packages. This means anaconda takes up more space on your hard drive (3GB+) and downloads/installs a lot slower. Installing packages with conda is easy so don’t hesitate to try miniconda if you want the extra space or control.

2) Clone this repository

	`$ git clone https://github.com/KSFreeman/pandas_tutorial.git`

3) In a terminal, navigate to the repository you just cloned  and open the jupyter notebook: 

	`$ cd pandas_tutorial`

	`$ jupyter notebook`

4) Run the first cell in the notebook by clicking anywhere inside of it and pressing ctrl + enter. The first two lines import the packages needed for the tutorial, if it runs without any warnings that means you are ready. If you installed miniconda instead of anaconda you will have to run these two commands in your terminal to get the numpy and pandas packages:

	`$ conda install numpy`

	`$ conda install pandas`






\* Note about anaconda versions -- Python has two releases that are currently supported, Python 2 and Python 3. They are pretty similar, but if you try to run a Python 2 program using Python 3 you will almost certainly get errors. Python 2 is being phased out but there’s still a lot of code out there written in Python 2, so if you want to run other people’s programs you need Python 2 and Python 3. One of the great features of conda is that you can set up different environments that use different versions of Python and switch between them. When you download ‘version 3.7’ of anaconda, you are not locked into only using Python 3.7 by any means. This just sets the ‘root’ (default) environment to use Python 3.7, but you can create as many other environments as you want and easily switch between them for running different programs. [How to set up and manage environments](https://conda.io/docs/user-guide/tasks/manage-environments.html)

