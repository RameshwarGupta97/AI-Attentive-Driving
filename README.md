# AI_Driving_Co-Pilot

## Steps to run the project - 
  * Download the project from the repo.
  * Install python 3.7 or above to the system.
  * Install python librabries given below as per file to run the code.
  * For PC file version please run ***pip install -r requirements.txt*** on CMD from the same directory to install the libraries.
  * This project has been built to keep in mind that camera is on dashboard and it is 30 degrees to the right side of the face.
  * To run the project into Laptop or webcam enabled system, run attention_detector_pc.py file in any python IDE.
  * To run the project into Rasberry Pi, run attention_detector_raspberry_pi.py file in any python IDE.
  * run command on CMD - py attention_detector_pc.py
  

* ### Python libraries needed to run the pc version (No need to install individually if you have installed using requirements.txt)- 
  * cv2/opencv (pip install opencv-python)
  * dlib (pip install dlib)
  * numpy (pip install numpy)
  * imutils (pip install imutils)
  * scipy (pip install scipy)
  * getmac (pip install getmac)
  * pygame (pip install pygame)
  
* ### Python libraries needed to run the raspberry pi version- 
  * cv2/opencv (pip install opencv-python)
  * dlib (pip install dlib)
  * numpy (pip install numpy)
  * imutils (pip install imutils)
  * scipy (pip install scipy)
  * getmac (pip install getmac)
  * pygame (pip install pygame
  * picamera (pip install picamera)
  * ICM20948 (pip install icm20948)

#### Note - To change the position of camera in the code, change variable -  
  *  origin = -30, for left.
  * origin  = 0, for front.
