# OpenCV-C-Program-for-Face-Detection



Sign In
Home
Saved Videos
Courses
Practice DS & Algo.
Algorithms
Analysis of Algorithms
Data Structures
Interview Corner
Languages
CS Subjects
GATE
Web Technologies
Software Designs
School Learning
Mathematics
Maths Notes (Class 8-11)
NCERT Solutions
RD Sharma Solutions
ISRO CS
UGC NET CS
Student
Jobs
GBlog
Puzzles
What's New ?
 Change Language
Related Articles
▲
Related Articles
OpenCV C++ Program for Face Detection
Opencv Python program for Face Detection
Face Detection using Python and OpenCV with webcam
OpenCV Python Tutorial
Reading an image in OpenCV using Python
Python OpenCV | cv2.imshow() method
Python OpenCV | cv2.imwrite() method
Python OpenCV | cv2.imread() method
Python OpenCV | cv2.cvtColor() method
Python OpenCV | cv2.rectangle() method
Python OpenCV | cv2.putText() method
Python OpenCV | cv2.circle() method
Python OpenCV | cv2.line() method
Python OpenCV – cv2.polylines() method
Perspective Transformation – Python OpenCV
Python OpenCV – Affine Transformation
Top 40 Python Interview Questions & Answers
Decorators in Python
Decorators with parameters in Python
Memoization using decorators in Python
Vector in C++ STL
The C++ Standard Template Library (STL)
Map in C++ Standard Template Library (STL)
std::sort() in C++ STL
Arrays in C/C++
Initialize a vector in C++ (6 different ways)
Bitwise Operators in C/C++
Converting Strings to Numbers in C/C++
Inheritance in C++
Object Oriented Programming in C++

OpenCV C++ Program for Face Detection
Difficulty Level : Medium
Last Updated : 17 Jun, 2017

This program uses the OpenCV library to detect faces in a live stream from webcam or in a video file stored in the local machine. This program detects faces in real time and tracks it. It uses pre-trained XML classifiers for the same. The classifiers used in this program have facial features trained in them. Different classifiers can be used to detect different objects.
Requirements for running the program:
1) OpenCV must be installed on the local machine.
2) Paths to the classifier XML files must be given before the execution of the program. These XML files can be found in the OpenCV directory “opencv/data/haarcascades”.
3) Use 0 in capture.open(0) to play webcam feed.
4) For detection in a local video provide the path to the video.(capture.open(“path_to_video”)).
