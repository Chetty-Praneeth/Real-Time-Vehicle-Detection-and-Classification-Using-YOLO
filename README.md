# Real Time Vehicle Detection and classification Using YOLO

## Overview
This project utilizes the YOLO (You Only Look Once) object detection model to track vehicles in a given video feed. The system detects the type of vehicle, calculates its speed, and maintains a count of vehicles passing through a designated area.

## Features
- **Real-time Vehicle Detection**: Identifies vehicles such as cars, buses, trucks, and motorcycles.
- **Speed Estimation**: Calculates the speed of detected vehicles.
- **Vehicle Counting**: Keeps track of the number of vehicles passing through a specified region.

## Requirements
- Python 3.x
- OpenCV
- YOLOv4 or YOLOv5 model
- NumPy
- Pandas
- Matplotlib (optional for visualization)

## Installation

1. Clone the repository:
    ```bash
git clone https://github.com/yourusername/vehicle-tracking-yolo.git

2. Install dependencies
    ```bash
pip install -r requirements.txt

3. Download YOLO weights and configuration files from the official YOLO repository

4. Run the vehicle tracking script
    ```bash
python vehicle_tracking.py --video input.mp4

# For real-time detection using a webcam
python vehicle_tracking.py --webcam

### Output:
<video width="500" controls>
  <source src="output/yolo_output.mov" type="video/mp4">
  Your browser does not support the video tag.
</video>

- Annotated video with bounding boxes and speed of vehicles.
- Vehicle count displayed in real-time.
- CSV log of detected vehicle types and speeds.

## Future Improvements
- Integrating license plate recognition.
- Enhancing speed estimation using optical flow techniques.
- Deploying the system as a web-based application.
