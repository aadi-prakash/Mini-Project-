# Mini-Project: Jackfruit Level Problem
TEAM NAME: 
Guru's Disciples

TEAM MEMBERS:
Akshat Sharma - PES2UG25CS046,
Aaditya Prakash - PES2UG25CS003,
A Abilash - PES2UG25CS001,
Aditya - PES2UG25CS033
____________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

**Project Overview**

This mini image processing tool demonstrates basic computer vision operations using a graphical user interface. The application allows the user to load an image and then perform three core tasks: counting red pixels, converting the image to grayscale, and detecting the dominant color in the image.
Problem Statement

The aim of the project is to:

    Count the number of red pixels in a given image based on predefined color thresholds.

    Convert a color image to its grayscale equivalent and save the output.

    Detect the dominant color in the image using clustering on pixel color values.

**Technologies Used**

    Python as the programming language.

    OpenCV for image processing operations (color space conversion, grayscale conversion, k-means clustering).

    NumPy for efficient pixel-level array operations.

    Tkinter and PIL for building the GUI and displaying images to the user.

**How the Application Works**

    The user selects an image file through the GUI.

    On clicking:

        “Count Red Pixels”: the program scans all pixels and counts those matching the red color criteria.

        “Convert to Grayscale”: the program converts the image to grayscale and saves it as a new file.

        “Detect Dominant Color”: the program applies k-means clustering on pixel colors to find and display the dominant RGB color.

