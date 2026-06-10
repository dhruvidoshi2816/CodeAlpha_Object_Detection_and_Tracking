# CodeAlpha_Object_Detection_and_Tracking

# SentinAI Intelligence Suite

## Overview

SentinAI Intelligence Suite is an AI-powered surveillance and analytics platform built using Computer Vision and Deep Learning technologies. The system provides real-time object detection, multi-object tracking, restricted area monitoring, entry/exit counting, and visual analytics through an interactive Streamlit dashboard.

The project was developed as part of an AI/ML internship to demonstrate practical applications of object detection and tracking in surveillance systems.

---

## Features

### Real-Time Object Detection

* Detects objects using YOLOv8.
* Supports webcam, image, and video inputs.
* Displays confidence scores and bounding boxes.

### Multi-Object Tracking

* Maintains unique IDs for detected objects.
* Tracks objects across consecutive frames.
* Reduces duplicate detections.

### Restricted Area Monitoring

* User-defined Regions of Interest (ROI).
* Detects unauthorized object entry into restricted zones.
* Generates visual alerts.

### Entry & Exit Counting

* Counts objects crossing predefined lines.
* Tracks movement direction.
* Provides real-time statistics.

### Analytics Dashboard

* Live detection statistics.
* Object count summaries.
* Session analytics and monitoring information.

### Multiple Input Sources

* Webcam Surveillance
* Image Analysis
* Video Analysis

### Interactive Streamlit Interface

* User-friendly dashboard.
* Real-time monitoring.
* Adjustable detection settings.

---

## Tech Stack

### Programming Language

* Python

### Computer Vision

* OpenCV

### Deep Learning

* YOLOv8 (Ultralytics)

### Tracking

* ByteTrack

### Dashboard

* Streamlit

### Data Processing

* NumPy
* Pandas

### Visualization

* Plotly

---

## Project Structure

```text
SentinAI-Intelligence-Suite/
│
├── streamlit_app.py
├── requirements.txt
├── README.md
│
├── object_detection_tracking/
│
├── models/
│
├── screenshots/
│
├── reports/
│
└── snapshots/
```

## Installation

### Clone the Repository

```bash
git clone <repository-url>
cd SentinAI-Intelligence-Suite
```

### Create Virtual Environment

```bash
python -m venv .venv
```

### Activate Environment

Windows:

```bash
.venv\Scripts\activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Run the Application

Start the Streamlit dashboard:

```bash
streamlit run streamlit_app.py
```

The application will open in your browser.

---

## Usage

### Webcam Surveillance

* Open the Webcam Surveillance module.
* Start the webcam feed.
* Monitor real-time detections and tracking.

### Image Analysis

* Upload an image.
* View detected objects and confidence scores.

### Video Analysis

* Upload a video.
* Analyze detections frame-by-frame.

### Analytics

* View detection summaries.
* Monitor object counts and activity statistics.

---

## Future Improvements

* Heatmap Analytics
* Event-Based Reporting
* Multi-Camera Support
* Advanced Alert System
* Cloud Deployment
* Performance Optimization

---

## Learning Outcomes

This project helped strengthen skills in:

* Computer Vision
* Object Detection
* Multi-Object Tracking
* Real-Time Video Processing
* Streamlit Development
* Performance Optimization
* Software Engineering Practices
