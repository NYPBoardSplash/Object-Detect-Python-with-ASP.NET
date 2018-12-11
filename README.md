# Object-Detect-Python-with-ASP.NET
#This project have two part, one with the project url build with ASP.NET framework 4.6.1 with single page application
#Another one is build with python, which have the ability of detecting car object by using opencv.

#As the file of asp.net too big, will not be able to upload on git.
Surf this url to locate it, 
#https://whataboutnyp.azurewebsites.net/monitoringpage

To run the python opencv project, these are all the dependencies need to be installed.
# opencv-car-detection
OpenCV Python program for Vehicle detection

How to run this program 
1) Open command prompt, make sure the following packages was install in your computer under this directory ("Your directory"/opencv-car-detection-master)
-----------------------------------------------
        flask,opecv, matplotlib, Pillow 
        from flask import Flask,jsonify,redirect, url_for
        from flask import abort
        import cv2
        from matplotlib import pyplot as plt
        import datetime
        import json,requests
        try:
            from StringIO import StringIO
        except ImportError:
            from io import StringIO,BytesIO #to save image into folder
        from PIL import Image #to save image into folder
------------------------------------------------
Else you have to install pip first and install the following package using the following command(For windows)
#pip install Pillow
#pip install flask
#pip install matplotlib
#pip install opencv-python
-----------------------------------------------
To run the program, simply type -->
#python Flask.py 
in command prompt
