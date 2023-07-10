# Object detection Web Application

## Description

This is a web application built using Flask and YOLOv8 object detection to perform object detection. It allows users to upload an image and perform machine learning to identify if there is any dog or cat. The application provides visual feedback and displays the detection results.

## Prerequisites

- Python 3.6 or higher

## Installation

1. **Clone the repository:**
git clone https://github.com/TnzTanim/Webapp-Object-detection

2. **Install the required dependencies:**
pip install -r requirements.txt

## Usage

1. **Start the Flask server:**

   python Webapp_Practice.py

2. **Open your web browser and visit `http://localhost:8080`.**

3. **Click the "Choose File" button and select an image  from your local machine.**

4. **The application will perform object detection on the uploaded image and display the detection results.**

## Project Structure

- `Webapp_Practice.py`: The main Python script that runs the Flask web application and handles the image detection process.
- `index.html`: The HTML template file for the web application's user interface.
- 'best.pt' contains the object detection model trained using Yolov8.




