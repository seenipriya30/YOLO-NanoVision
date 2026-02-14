YOLONanoVision
Overview

YOLONanoVision is an AI-powered object detection project built using YOLOv8 (Ultralytics) and OpenCV in Python. This system allows for accurate detection of multiple objects in images, providing annotated visual outputs along with a list of detected object classes. Designed for efficiency and scalability, YOLONanoVision uses the lightweight YOLOv8 Nano model to enable fast inference while maintaining reliable detection performance.

Features

Detect multiple objects in any input image.

Annotates detected objects with bounding boxes.

Displays the annotated image within the program.

Saves the detection results for further use.

Prints detected object names and total object count.

Lightweight and fast inference using YOLOv8 Nano.

Technologies & Libraries

Python 3.x

YOLOv8 (Ultralytics) – state-of-the-art object detection.

OpenCV – image processing and visualization.

Matplotlib – optional, for inline image display in notebooks.

Project Structure
YOLONanoVision/
│
├── detect.py           # main detection script
├── notebook.ipynb      # optional original Colab notebook
├── requirements.txt    # dependencies
├── README.md           # project description
├── images/             # input images (example: car.jpg)
└── outputs/            # annotated output images


detect.py – Python script for running YOLOv8 object detection on a single image.

images/ – folder containing input images for detection.

outputs/ – folder where annotated images will be saved.

notebook.ipynb – Colab notebook version of the project (optional for demonstration or experimentation).

Installation

Clone the repository:

git clone https://github.com/YOUR_USERNAME/YOLONanoVision.git
cd YOLONanoVision


Install required dependencies:

pip install -r requirements.txt

Usage

Place your image(s) inside the images/ folder.

Open detect.py and update the image path if needed:

image_path = "images/car.jpg"


Run the detection script:

python detect.py


The script will:

Display the annotated image.

Save the annotated image in the outputs/ folder.

Print detected object names and total count in the console.

Sample Output

Input Image: images/car.jpg

Output Image: outputs/detected_car.jpg

Detected Objects:

car

person

traffic light
Total Objects Detected: 3

(Replace these with actual results from your run)

Advantages

Lightweight and fast due to YOLOv8 Nano model.

Easy to use and integrate into larger projects.

Clear folder structure and script-based workflow.

Provides both visual and programmatic object detection outputs.

Future Enhancements

Real-time video or webcam detection.

Batch image detection.

Adjustable confidence threshold and NMS (non-max suppression).

Streamlit or Flask interface for interactive demos.

Integration with cloud storage or APIs for scalable usage.
