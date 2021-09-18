# Alarm-Clock-with-GUI
Python Project for Beginners – Alarm Clock with GUI. Being a beginner it’s critical to work in the right direction. To master a programming language, you should work on projects. In this article, we will develop a basic python project – Alarm clock.

# Develop an Alarm Clock
## About the Python Project
The objective of our project is to implement an alarm clock using Python. Python consists of some very innovative libraries such as datetime and tkinter which help us to build the project using the current date and time as well as to provide a user interface to set the alarm according to the requirement in 24-hour format.

## Prerequisites
This project requires good knowledge of Python and GUI (Graphic User Interface). Python when combined with Tkinter provides a fast and easy way to create GUI applications. Tkinter provides a powerful object-oriented interface to the Tk GUI toolkit. All the modules used need not be downloaded beforehand like the other libraries like NumPy, thus this project will be user friendly and accessible in any virtual environment used for python programming.

## Project File Structure
First, let’s check the steps to build an Alarm Clock program in Python:
Importing all the libraries and modules required
Putting forward a while loop which takes the argument of the time, the user wants to set the alarm on and automatically breaks when the time is up, with sound
Create a display window for user input.
#1. First, we import all the necessary libraries and modules:

# Importing all the necessary libraries to form the alarm clock:
from tkinter import *
import datetime
import time
import winsound

Explanation:
Tkinter module belongs to a standard library of GUI in Python. It helps us to create a dialog box with any information that we want to provide or get from the users.
Datetime and time modules in python help us to work with the dates and time of the current day when the user is operating python and to manipulate it too.
Winsound module provides access to the basic sound playing machinery provided by Windows platforms. This is useful to generate the sound immediately when a function is called.
