@'
# Collision Detection using YOLOv8

This project implements real-time collision detection using YOLOv8 for image and video-based collision detection.

---

## Model File (Required)

The full trained model file exceeds GitHub's 100MB size limit and is hosted externally.

Download the main model from:

https://drive.google.com/file/d/1pzD3KfiF8-YrL6AlwGh6lRvmgOS2A5qn/view?usp=sharing

After downloading, place the file inside:

model/yolo_best.onnx

Note:
Smaller model versions are already included in the repository.
The full model provides better accuracy.

---

##  Setup Instructions

1. Create and activate a virtual environment (recommended)

   python -m venv venv  
   venv\Scripts\activate  

2. Upgrade pip

   python -m pip install --upgrade pip setuptools wheel

3. Install required dependencies

   pip install -r requirements.txt

4. Run the project

   python start.py

---

##  Project Structure

- start.py – Main entry point  
- YoloVideoBased.py – Video collision detection  
- YoloImageBased.py – Image collision detection  
- model/ – Model files  
- requirements.txt – Dependencies  

---

## Features

- YOLOv8-based object detection  
- Image-based collision detection  
- Video-based collision detection  
- Modular and structured code  

---

'@ | Out-File -Encoding utf8 README.md