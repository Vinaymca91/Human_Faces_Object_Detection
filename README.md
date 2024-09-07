Human Faces Object Detection Application
This repository hosts an interactive application developed using Streamlit and the YOLOv8n model for real-time object detection and tracking. The application allows users to detect and track objects in images, videos, or webcam feeds. It offers customizable settings such as selecting specific object classes and adjusting confidence thresholds, making it a versatile tool for various use cases.

Features
Human Faces Object Detection Application Detect and track objects in real-time from video files or webcam feeds.
Image and Video Support: Easily upload images or videos for object detection.
Customizable Detection Settings:
Select specific object classes to detect.
Adjust confidence thresholds to refine detection results.
User-Friendly Interface: Simple and intuitive interface built using Streamlit, ensuring accessibility for both technical and non-technical users.
Requirements
Python 3.7 or later
Streamlit
OpenCV
Ultralytics YOLOv8
Other dependencies as listed in requirements.txt

Installation
Clone the repository:

bash
Copy code
git clone https://github.com/Vinaymca91/Human_Faces_Object_Detection.git
cd repo-name
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Run the application:

bash
Copy code
streamlit run app.py

Usage
Launch the Streamlit app in your web browser.
Upload an image or video, or select the webcam option for live object detection.
Customize the settings by choosing object classes and setting the confidence threshold.
View the detection results with bounding boxes around the detected objects.
Model
This application uses the YOLOv8n model, a lightweight and efficient version of the YOLO (You Only Look Once) family, optimized for real-time object detection tasks. The model offers a balance between performance and speed, making it suitable for both real-time applications and batch processing.

Acknowledgments
Streamlit: A big thank you to the creators of Streamlit for providing an easy-to-use framework to build and deploy data-driven applications.
YOLOv8n Model: Special thanks to the Ultralytics team for developing and open-sourcing the YOLOv8n model, which powers the object detection functionality in this app.
