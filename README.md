# Driver Drowsiness Detection

This is a simple Python project that detects driver drowsiness in real-time using a webcam.  
It uses **OpenCV** for video capture and **dlib** to detect facial landmarks.  
If the driver’s eyes stay closed for too long, it plays a beep sound to alert them.

---

## Features
- Detects eyes using dlib’s 68 facial landmarks  
- Calculates **Eye Aspect Ratio (EAR)** to check if eyes are closed  
- Plays an alert sound if eyes remain closed for several frames  
- Runs in real-time using your webcam  

---

## Requirements

- Python 3.8 or above  
- OpenCV  
- dlib  
- imutils  
- scipy  
- pygame  

Install with:

```bash
pip install opencv-python dlib-bin imutils scipy pygame
