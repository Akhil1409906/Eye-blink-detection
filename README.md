# Real-Time Eye Blink Detection and Counting

This project uses OpenCV, dlib, and Flask to detect and count eye blinks in real-time using a webcam feed. It utilizes dlib's facial landmark detection model to locate key points around the eyes, calculates the eye blinking ratio, and displays the results in a web interface.

## Technologies Used
- Python
- OpenCV
- dlib
- Flask
- HTML/CSS
- JavaScript

## Features
- Real-time eye blink detection using webcam feed.
- Detects and counts the number of eye blinks.
- Displays blink count and visual feedback for each blink.
- Web interface using Flask with HTML and CSS.

## Installation

### Prerequisites
1. Install Python (>=3.6) from [python.org](https://www.python.org/).
2. Install necessary Python libraries using `pip`:
   ```bash
   pip install opencv-python dlib flask numpy
