# track-obj-s
This project is a single script project used to track object either in a live video feed from a webcam or in a video file (like a movie).


# Pre-requisites

-->Install anaconda (not mandatory)
You can either use a virtual environment to install all your dependencies for version control.

--> Use pycharm to create the virtual environment
1. Install the following packages (in the venv) before running the script
  a. opencv-contrib-python (3.3+ or higer)
  b. imutils
  c. argparse
  
Open the CLI(command line interface) to activate the virtual env

following type of arguments can be passed to the command line interface to use the various type of trackers

 + "csrt" - to use CSRT tracker
 + "kcf"  - to use KCF tracker
 + "boosting" - to use Boosting tracker
 + "mil"  - to use MIL tracker
 + "tld"  - to use TLD tracker
 + "medianflow" - to use MedianFlow tracker
 + "mosse" - tos use MOSSE tracker
 
 
--> In the CLI cd(change directory) to the location where you have created the virtual environement
  + enter the following command
  
  python opencv_object_tracker.py --tracker trackerType
  
  eg: opencv_object_tracker.py --tracker csrt
  
--> The Tracker Object window will open
    +press the "s" key to freeze the frame and select the object the you want to track using the crosshairs
    +press the enter or space key to confirm the selection.
    +try moving the object around the screen
    +press "q" key to exit the window

