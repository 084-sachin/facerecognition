# Face Recognition

Face Recognition using OpenCV in Python



### Prerequisites

Open The Terminal in the workspace and Run the following command
**pip3 install opencv-contrib-python**
The project is ready to function after this

The project serve two functionalities
1) Open the tester.py file, run the file, it will identify the image stored in TestImages folder with the images kept in trainingImages folder and will show the name.
    I have kept some celebrity images in the folder to test it 
2) Open the videoTester.py file, it will recognize the live video with the images kept in training Images folder.
    For testing this, we can make a separate folder with our images (30-40) and then enter the name in the dictionary line 11 in videoTester.py file
    If the match is greater than or equal to 39%, it will show the result. We can increase or decrease the accuracy but it is preferred to keep it in this range.

