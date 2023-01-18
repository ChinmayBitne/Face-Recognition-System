# Face-Recognition-System
A python project implemented by me and my teammates


To read run the face recognition system program (made by us) requires few libraries to be installed:
1.	Tkinter
2.	OpenCV
3.	Pathlib
4.	NumPy					To install them use command: 
5.	Pandas					     pip install “library_name”
6.	Pillow
7.	Shutil
8.	OS

Steps To run the program: -
1.	Install all the above-mentioned libraries with latest python version.
2.	Open the program and execute it in the compiler (as per user).
3.	After the program starts running, then maximize the Tkinter window.
4.	A GUI will be displayed which contains the attributes (like to add roll no, name, add database, etc.).
5.	Now enter the ID or Roll No of the user and click on “Add Database”.
6.	The new window will be opened with camera to scan face.
7.	Slightly move your face in left and right direction by which the edges of the face will be getting scanned.
8.	Nearly about 60 images are getting captured then the camera window is closed.
9.	After that you have to click on “Train Faces” to create a histogram and to store the face of a person(user).
10.	Now your face has been stored in the database, then by clicking on “Recognize Face” again the camera window will be opened which will show the face recognized with the tag [‘Roll No-Name’].
11.	And the last option “Exit” is to exit the program after which the program execution will be ended.
