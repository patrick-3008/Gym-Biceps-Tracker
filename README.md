# Gym-Biceps-Tracker
<video src="https://github.com/user-attachments/assets/14a43e9e-4994-4ffd-aae1-f04de9316999" controls width="300">
  This browser does not support HTML video.
</video>

## Overview
Gym-Biceps-Tracker is a Python application that uses MediaPipe to track and analyze biceps curls via your camera. The application helps you monitor your exercise form and count your reps by leveraging computer vision and machine learning technologies.

## Features
<uol>
  <li><b>Real-time Biceps Curl Detection:</b> Uses MediaPipe to detect and track your arm movements.</li>
  <li><b>Repetition Counting:</b> Automatically counts the number of biceps curls performed.</li>
  <li><b>Form Feedback:</b> Provides visual and textual feedback to help you maintain proper form.</li>
</uol>

## Requirements
<uol>
  <li>Python 3.7 or higher</li>
  <li>MediaPipe</li>
  <li>OpenCV</li>
  <li>NumPy</li>
</uol>

You can install the necessary packages using pip:
<code>pip install mediapipe opencv-python numpy</code>

## Usage
<ol>
  <li>Ensure your camera is connected and properly set up.</li>
  <li>Run the application</li>
  <li>The application will open a window showing the live video feed from your camera with detected biceps curls and feedback.</li>
</ol>

## How it works
<uol>
  <li><b>MediaPipe:</b> Used for pose estimation and tracking the key points of your arm.</li>
  <li><b>OpenCV:</b> Handles the camera feed and visualizations.</li>
  <li><b>NumPy:</b> Provides mathematical operations required for detecting curl reps and form analysis.</li>
</uol>

## Contributing
Feel free to fork the repository and submit pull requests. For major changes or features, please open an issue to discuss them first.

## Contact
For any questions or support, please open an issue on the GitHub repository or contact patricknaashat@yahoo.com
