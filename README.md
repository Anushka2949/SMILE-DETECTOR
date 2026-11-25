# Smile Detector

Real-time face and smile detector using a laptop webcam and OpenCV.

## Requirements
- Python 3.8
- opencv-python

## How to run
1. Install OpenCV: `pip install opencv-python`
2. Run the program: `python smile.py`
3. Press `q` to quit.

## How it works
- Takes a picture from the camera again and again
- Converts it to grayscale
- Finds the face and draws a box around it
- Looks for a smile inside the face and shows "Smiling :)"
