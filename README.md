# SitFit
### By:
- Nada AbdElHalem
- Reham Karam
- Salma Shamel
- Samuel Medhat
- Younan Nagy

# Project Description

SitFit is a personal assistant desktop app for a healthy and comfortable laptop experience. Check video [here](https://youtu.be/UXKte1Qf39A).



# Goals

1. Warns user when his/her position along with the screen’s position are not in the right position.
2. It advises the user what to do to set the sitting position correctly.
3. Warns the user after sitting continuously for a long time.
4. Detects if nobody is sitting in front of the computer.
5. Warns the person if he is not blinking enough this helps protect his eyes from dehydration.


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them.

```
Download Anaconda from the link [https://www.anaconda.com/distribution/#download-section].
Note that we are working with python 3.6.8
```

### Installing


First you need to setup an environment in anaconda navigator,make sure to select python vesion 3.6.8 and then download the next libraries in this environment.
```
pip install cmake
pip install dlib --verbose                                    
conda install -c pjamesjoyce imutils
conda install -c anaconda scipy
conda install -c anaconda opencv
conda install -c anaconda numpy
conda install -c anaconda py-notifier
conda install -c anaconda win10toast
conda install -c anaconda pillow
```

## Executing
```
python Sit_fit.py
```
