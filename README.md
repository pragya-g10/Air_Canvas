# Air_Canvas
A Computer Vision project-

We know that artists create paintings on a canvas. But what if we can paint on air just by waving our hands. So, in this project, we are going to build an air canvas using OpenCV and Python.

Requirements: 
 

1-Python3 
 
2-NumPy 
 
3-OpenCV 
 
Algorithm: 
 

1-Start reading the frames and convert the captured frames to HSV color space (Easy for color detection). 
 
2-Prepare the canvas frame and put the respective ink buttons on it. 
 
3-Adjust the track bar values for finding the mask of the colored marker. 
 
4-Preprocess the mask with morphological operations (Eroding and dilation). 
 
5-Detect the contours, find the center coordinates of largest contour and keep storing them in the array for successive frames (Arrays for drawing points on canvas). 
 
6-Finally draw the points stored in an array on the frames and canvas.
 
