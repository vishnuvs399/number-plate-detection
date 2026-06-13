# Vehicle Number Plate Detection and Recognition

## Overview

This project is a Python-based Vehicle Number Plate Detection and Recognition system developed using OpenCV and EasyOCR. It extracts text from vehicle images, identifies number plate information, and displays the detected text with bounding boxes and confidence scores.

## Features

* Upload and process vehicle images
* Automatic text extraction using OCR
* Detection of number plate information
* Bounding box visualization for detected text
* Confidence score-based filtering
* Easy-to-use implementation in Google Colab

## Technologies Used

* Python
* OpenCV
* EasyOCR
* NumPy
* Matplotlib

## Project Workflow

1. Upload a vehicle image.
2. Load and preprocess the image.
3. Apply EasyOCR to detect text regions.
4. Extract and recognize number plate text.
5. Draw bounding boxes around detected text.
6. Display the final output image and recognized text.

## Applications

* Automatic Number Plate Recognition (ANPR)
* Smart Parking Systems
* Traffic Monitoring
* Vehicle Identification and Tracking

## Installation

```bash
pip install opencv-python-headless easyocr matplotlib numpy
```

## Usage

1. Run the Python script or Google Colab notebook.
2. Upload an image containing a vehicle.
3. View the detected number plate text and processed image.

## Future Enhancements

* Dedicated number plate localization using object detection models.
* Real-time video stream processing.
* Multi-language number plate recognition.
* Integration with vehicle databases.

## Author

Vishnu VS
