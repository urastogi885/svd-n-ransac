# ENPM673 - Homework 1

## Overview

The homework consists of 3 parts with a non-coding and 2 coding problems. The non-coding problem covers with basic optics 
concepts while the coding problems cover curve fitting algorithms and perception algorithms such as SVD (Singular Value 
Decomposition).

Here, we will cover the instructions to run the coding problems.

## Dependencies

- Python3
- Python3-tk
- Python3 Libraries: Pandas, Numpy, and Matplotlib

## Install Dependencies

- Install *Python3*, *Python3-tk*, and the necessary libraries: (if not already installed)
````
sudo apt install python3 python3-tk
pip3 install pandas numpy matplotlib
````
- Check if your system successfully installed all the dependencies
- Open terminal using ````Ctrl+Alt+T```` and enter ````python3````
- The terminal should now present a new area represented by ````>>>```` to enter python commands
- Now use the following commands to check libraries: (Exit python window using ````Ctrl+Z```` if an error pops up while 
running the below commands)
````
import tkinter
import pandas as pd 
import numpy as np
import matplotlib.pyplot as plt
````

## Run

- Extract the compressed folder onto your system
- Go into the *Code* sub-directory
- Open a terminal window by right-clicking on empty space within the folder and then click ````Open in Terminal````
- Make sure all dependencies have been installed and run program for problem 2:
````
python3 problem_2.py
````
- The program launches 4 plots: next one will pop up once you close the current one
- Run program for problem 3:
````
python3 problem_3.py
````
- THe program will print 4 matrices for SVD
