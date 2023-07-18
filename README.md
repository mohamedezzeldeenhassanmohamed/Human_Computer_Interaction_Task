# Volume-control-using-hand-gesture-using-python-and-openCv
Here we are trying to process a video so that we can control volume of device with help of camera using the tips our thumb and index finger.

https://github.com/mohamedezzeldeenhassanmohamed/Human_Computer_Interaction_Task/assets/94178842/281a2b31-6673-479a-8ce6-e6e67f9bcff1

# Things used in this project
1- Jupyter Notebook.
2- OpenCV.

# Story
INTRODUCTION
Gesture recognition helps computers to understand human body language. This helps to build a more potent link between humans and machines, rather than just the basic text user interfaces or graphical user interfaces (GUIs). In this project for gesture recognition, the human body’s motions are read by computer camera. Thecomputer then makes use of this data as input to handle applications. The objective of this project is to develop an interface which will capture human hand gesture dynamically and will control the volume level.

NumPy is a library for the Python programming language, adding support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays.

Pycaw : Python Audio Control Library

Mediapipe is an open-source machine learning library of Google, which has some solutions for face recognition and gesture recognition, and provides encapsulation of python, js and other languages. MediaPipe Hands is a high-fidelity hand and finger tracking solution. It uses machine learning (ML) to infer 21 key 3D hand information from just one frame. We can use it to extract the coordinates of the key points of the hand.

WORKING PRINCIPLE
The camera in our device is used for this project. It detects our hand with points in it so as it can see the distance between our thumb finger tip and index finger tip. The distance between the points 4 and 8 is directly proportional to the volume of device.

METHODOLOGY/APPROACH
Detect hand landmarks
Calculate the distance between thumb tip and index finger tip.
Map the distance of thumb tip and index finger tip with volume range. For my case, distance between thumb tip and index finger tip was within the range of 30 – 350 and the volume range was from -63.5 – 0.0.
In order to exit press ‘Spacebar'

![h](https://github.com/mohamedezzeldeenhassanmohamed/Human_Computer_Interaction_Task/assets/94178842/05e9ddfc-88a9-4858-8b73-499b155f33bc)

# WORKING PRINCIPLE
The camera in our device is used for this project. It detects our hand with points in it so as it can see the distance between our thumb finger tip and index finger tip. The distance between the points 4 and 8 is directly proportional to the volume of device.

# METHODOLOGY/APPROACH
 * Detect hand landmarks
 * Calculate the distance between thumb tip and index finger tip.
 * Map the distance of thumb tip and index finger tip with volume range. For my case, distance between thumb tip and index finger tip was within the range of 30 – 350 and the volume range was from -63.5 – 0.0.
 * In order to exit press ‘Spacebar'
# ADVANTAGES:
 * Easy to use
 * Hassle free
 * Fun to use
 * More interactive
# DISADVANTAGES:
 * Cant be used for long distance
 * Sometimes not accurate
 * Requires a decent camera
 * May be confused by two palms
