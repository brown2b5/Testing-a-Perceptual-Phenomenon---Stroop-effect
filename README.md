# Testing a Perceptual Phenomenon - Stroop effect

In a Stroop task (1), participants are shown words with differing colors of ink and the time it takes the participant to state the color of the ink is recorded.  This happens under two different conditions;  the congruent condition for which the colored words match the ink for which they are printed (black written in black ink, blue written in blue ink);  the incongruent condition for which the colored words do not match the ink for which they are printed (black written in purple ink, blue written in red ink).  The purpose of this project is to examine some descriptive statistics regarding the difference in time it takes for participants to state the color of the ink correctly under the incongruent and congruent conditions and to see if the mean difference in time to state the correct color between the incongruent and congruent conditions is significantly greater than 0. Because participants will be perceiving contrasting conditions in the incongruent condition (non-matching color of word with reading of a different color), my expectation is that the  mean difference in time between the incongruent and congruent conditions will be significantly greater than 0. The incongruent condition should cause confusion in the participants.

# Programming Environment
I use Anaconda, a distribution of packages built for data science to create and separate my programming environments ([download here](https://www.anaconda.com/download/)).  For anyone using Anaconda, it is suggested to first upgrade conda by running the following command from the Anaconda prompt if you haven't done so in a while:
```
conda upgrade conda
conda upgrade --all
```

For those with Anaconda, I have included a .yaml file (stroop_effect.yaml).  To create the environment in Anaconda, run the following from the Anaconda prompt:
```
conda env create -f stroop_effect.yaml
```
This will create an environment with the same name as the .yaml file.  
For those without Anaconda, I have included a requirements.txt file with the necessary programming packages and versions.  

This project was completed using a jupyter notebook with the latest version of Python 3.  My jupyter notebook (Test a Perceptual Phenomenon.ipynb) can be opened in Anaconda.  First, you will need to activate the environment created with the .yaml file by running the following in the Anaconda prompt:
```
activate stroop_effect
```
After activating the environment, open a jupyter notebook by running the following in the Anaconda prompt:
```
jupyter notebook
```
Just make sure you are in the folder which contains the .ipynb file.  The notebook will appear in a web browser.

The python packages I use in this project are [pandas](https://pandas.pydata.org/), [numpy](http://www.numpy.org/) and [matplotlib](https://matplotlib.org/).  Using the .yaml file I've provided to create your environment or installing the packages in the requirements.txt file should make things good to go with using these packages.  I refer you to the links I've provided for documentation and tutorials on each of these packages.

# How to make contributions
I am certainly open to contributions from others as this project moves forward.  To contribute, first clone the repository onto your local machine by running the following command in git:
```
git clone https://github.com/brown2b5/Testing-a-Perceptual-Phenomenon---Stroop-effect
```

After making changes to the project, submit a pull request and we will discuss the possibility of merging the changes to the master branch.

# License and copyright

### Pandas
Copyright (c) 2008-2012, AQR Capital Management, LLC, Lambda Foundry, Inc. and PyData Development Team

Licensed under the [BSD 3-Clause License](https://github.com/brown2b5/Testing-a-Perceptual-Phenomenon---Stroop-effect/blob/master/PANDAS%20License.txt).

### matplotlib
© Copyright 2002 - 2012 John Hunter, Darren Dale, Eric Firing, Michael Droettboom and the Matplotlib development team; 2012 - 2018

Licensed under the [PSF License](https://github.com/brown2b5/Testing-a-Perceptual-Phenomenon---Stroop-effect/blob/master/MATPLOTLIB%20License.txt).

### Python
Copyright © 2001-2018 Python Software Foundation; All Rights
Reserved

Licensed under the [PSF License](https://github.com/brown2b5/Testing-a-Perceptual-Phenomenon---Stroop-effect/blob/master/PYTHON%20License.txt).

### Anaconda

(c) 2017 Continuum Analytics, Inc. (dba Anaconda, Inc.). https://www.anaconda.com. All Rights Reserved

Licensed under [BSD 3-Clause License](https://github.com/brown2b5/Testing-a-Perceptual-Phenomenon---Stroop-effect/blob/master/CONDA%20License.txt).

### Jupyter

Copyright 2018 Project Jupyter

Licensed under [BSD 3-Clause License](https://github.com/brown2b5/Testing-a-Perceptual-Phenomenon---Stroop-effect/blob/master/JUPYTER%20License.txt).

### Numpy

Copyright (c) 2005, NumPy Developers

Licensed under [Numpy License](https://github.com/brown2b5/Testing-a-Perceptual-Phenomenon---Stroop-effect/blob/master/NUMPY%20License.txt).


#                       **References**
Reference 1: https://www.psytoolkit.org/lessons/stroop.html
