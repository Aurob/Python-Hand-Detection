# Python Hand Detection

This project uses Haar Feature-based Cascade Classifiers to detect hands in an image (or a frame from webcam).

For more information regarding using python for Haar Feature object detection see this link. (The detection part of this project was taken from this link and altered to fit the project):
[Face Detection using Haar Cascades](https://docs.opencv.org/3.4/d7/d8b/tutorial_py_face_detection.html)

## Detecting hands in python 3 using openCV

This projectwas written and tested in python 3.4+. Both required libraries are availble in python 2.7, but no testing was done in that version, so further maintenence will be required on your end to make it work in python 2.7.

You will need to install two python libraries for this project to work, opencv-python and imutils

You can install them using pip:
```
pip install opencv-python

pip install imutils
```
If any issues occur on installation, or for further information regarding these libaries, reference the documentation for each library:

[opencv-python](https://pypi.org/project/opencv-python/)

[imutils](https://github.com/jrosebr1/imutils)

If you need help using or installing pip see this link for help:
[Install pip for python](https://www.makeuseof.com/tag/install-pip-for-python/)

The haar-cascade used in this project was created by github user [Aravindlivewire](https://github.com/Aravindlivewire/Opencv/blob/master/haarcascade/aGest.xml)
