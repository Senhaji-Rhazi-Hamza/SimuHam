#Project 
## Intro
-the project here is about implementing a model that does some treatment on 
a data given in a csv format

## Linux Environement requirement
1-python 3.5

2-numpy

3-jupyter

4-matplotlib

## How to install
### 1)
-sudo add-apt-repository ppa:deadsnakes/ppa

-sudo apt-get update

-sudo apt-get install python3.5

### 2)
-sudo pip3 install numpy

### 3)
-sudo pip3 install numpy

-sudo pip3 install jupyter

### 4 
-python -mpip install -U pip

-python -mpip install -U matplotlib


or


-git clone https://github.com/matplotlib/matplotlib

-cd matplotlib

-python3 setup.py build

-sudo python3 setup.py install


## what have been done
-a class Sumydyne have been defined when instantiated, and the method
process is called the first time it process the data given in input
for a number of years then when it finishes it record the state of the 
data in another csv file called "currentState.csv"

-when the method process is called again for a certain number of 
years it load the data recorded in "currentState.csv" instead of
getting the input

-all the gained, lost, and regained are recorded in the class
so you could plot in histogram the values in function of years
more than that you could choose the years you want to plot 
in the histogram

-when plot is called, it save the last histogram 
in stat.png
## how to test
in the root file type cmd : jupyter notebook

when  Simudyne.ipynb is opened click on run :
the first cell is for imports
the second is for class definition
the tird is for test

do not hesitate to contact me if you need more precision 
hamza.senhaji-rhazi@epita.fr



