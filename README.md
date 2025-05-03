# Face and Object Detection System

## Overview
This project aims to create a real-time AI system for detecting faces and objects concurrently using computer vision techniques. The system utilizes the facial_recognition library for face recognition and the YOLOv3 object detection model for object detection.

## Features
- Detects known faces and labels them with their names.
- Detects unknown faces and saves their images for later review.
- Detects objects, such as bottles, and labels them in the video stream.

## Requirements
- Python 3.xx
- OpenCV
- Matplotlib
- Tkinter
- facial_recognition library
- YOLOv3 weights and configuration files

## Usage
1. Clone the repository.
2. Install the required dependencies using pip which are listed in requirements.txt:
```
pip install -r requirements.txt
```
3. Run the `main_video.py` script:
```
python main_video.py
```

## Directory Structure
- `images/`: Contains encoding images for known faces.
- `unknown/`: Directory to save images of unknown faces.
- `yolov3.weights` and `yolov3.cfg`: YOLOv3 model files.

## Credits
- YOLOv3: https://github.com/pjreddie/darknet
- facial_recognition library: https://github.com/ageitgey/face_recognition

## License
This project is licensed under the GNU General Public License v3.0 - see the LICENSE file for details.

