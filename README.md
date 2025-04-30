# fire-detection
flame detection using computer vision
A simple real-time flame detection system using YOLOv8 and OpenCV on Windows.
Features:
  Detects fire with a pre-trained YOLOv8 model
  Plays beep alert on detection (Windows only)
  Overlays a warning icon and text on video feed
Requirements:
  Python 3.8+ 
  ultralytics, opencv-python, numpy
  Windows OS for audio alert
Installation:
  pip install ultralytics opencv-python numpy
  Download best.pt and fire_warning.png into the project folder.
Usage:
  python flame_detection.py
  Press q to quit.
Config:
  FIRE_MODEL_PATH: path to best.pt
  CONFIDENCE_THRESHOLD: detection confidence
  FIRE_WARNING_IMAGE_PATH: path to PNG warning icon
License:
  MIT
