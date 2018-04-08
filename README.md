# Testing a Perceptual Phenomenon - Stroop effect

In a Stroop task (1), participants are shown words with differing colors of ink and the time it takes the participant to state the color of the ink is recorded.  This happens under two different conditions;  the congruent condition for which the colored words match the ink for which they are printed;  the incongruent condition for which the colored words do not match the ink for which they are printed.  The purpose of this project is to examine some descriptive statistics regarding the time it takes for participants to state the color of the ink correctly under each of the conditions and to see if there is a significant difference between the mean times for each of the two conditions.

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

This project was completed using a jupyter notebook with the latest version of Python 3.  My jupyter notebook (a .ipynb file) can be opened in Anaconda.  First, you will need to activate the environment created with the .yaml file by running the following in the Anaconda prompt:
```
activate stroop_effect
```
After activating the environment, open a jupyter notebook by running the following in the Anaconda prompt:
```
jupyter notebook
```
Just make sure you are in the folder which contains the .ipynb file.  The notebook will appear in a web browser.

The python packages I use in this project are [pandas](https://pandas.pydata.org/), [numpy](http://www.numpy.org/) and [matplotlib](https://matplotlib.org/).  Using the .yaml file I've provided to create your environment or installing the packages in the requirements.txt file should make things good to go with using these packages.


####                       **References**
Reference 1: https://www.psytoolkit.org/lessons/stroop.html
