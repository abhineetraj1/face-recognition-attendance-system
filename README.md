# Face recognition attendance system
This is a demo of face recognition attendance system on live video from your webcam. It includes some basic performance tweaks to make things run a lot faster:
*	Process each video frame at 1/4 resolution (though still display it at full resolution)
*	Only detect faces in every other frame of video.

### PLEASE NOTE :-
*	This example requires OpenCV (the `cv2` library) to be installed only to read from your webcam.
*	OpenCV is *not* required to use the face_recognition library. It's only required if you want to run this
*	specific demo. If you have trouble installing it, try any of the other demos that don't require it instead.

## Features:-
*	Requires less memory (RAM) to operate
*	Recognizes known faces from real time live video
*	full automated, no need to maintain registeration system
*	Easy to add new students
*	Easy to remove old students
## Working
*	It automatically create a folder with today's date, then create another folder inside that folder, with section name as a folder, and in that it creates a file with a name of roll number. If the student is absent or his/her face is not shown or recognised in camera then it won't create student roll number file in that folder.
*	File structure :-
Defined file tree structure of operated program

```
blocks
--date
----section
------roll number
------roll number
------roll number
----section
------roll number
------roll number
------roll number
--date
----section
------roll number
------roll number
------roll number
----section
------roll number
------roll number
------roll number
```

Example of file tree system of operated program
```
blocks
--27-12-23
----A18
------22049XX
------22049XY
------22049XZ
----A19
------22050XX
------22050XY
------22050XZ
--28-12-23
----A18
------22049XX
------22049XY
------22049XZ
----A19
------22050XX
------22050XY
------22050XZ

```

## Installation
*	Download python3.x
*	Install all the required libraries :-
```
pip3 install -r requirements.txt
```
## Setup
*	If you want to add student's face data, then click the picture of student's front face.
*	Make sure image file should be in jpg format
*	Rename the image file of student as "section-roll.jpg"
*	Example is there in students folder  (A19-2205007.jpg, A19-22050XX.jpg, etc).


## Languages used:
<a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> </p>

## Author
*	[abhineetraj1](http://github.com/abhineetraj1)
