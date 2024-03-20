## AI Virtual Painter

This project implements an AI Virtual Painter using Python and OpenCV. The application allows users to draw on a virtual canvas using hand gestures captured through a webcam.

**Features**

*Hand Tracking*:  Utilizes the hand_tracking_module to detect and track hand gestures in real-time.<br>
*Gesture Recognition*:  Recognizes gestures to switch between drawing mode and selection mode.<br>
*Color Selection*:  Allows users to select different drawing colors by hovering over predefined color regions on the screen.<br>
*Brush Thickness Control*:  Enables users to adjust the brush thickness for drawing strokes.<br>
*Canvas Interaction*:  Provides functionalities for drawing, erasing, and switching between different drawing modes.<br>

**Requirements:**

* Python 3.x
* OpenCV library (`pip install --upgrade opencv-python`)
* Mediapipe library(`python -m pip install mediapipe`)
* [hand_tracking_module.py](hand_tracking_module.py)

**Instructions:**

1. Download or clone the repository.
2. Install the required libraries 
`pip install opencv-python`
`python -m pip install mediapipe`
4. Run the application using `python AI_VIRTUAL_PAINTER.py`.

