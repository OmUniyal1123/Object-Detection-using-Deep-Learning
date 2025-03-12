# Object-Detection-using-Deep-Learning
Real-time object detection using OpenCV and SSD MobileNet v3, identifying objects from the COCO dataset with confidence scores. The script captures video from a webcam, detects objects, and displays results with bounding boxes.

# Object Detection using OpenCV and SSD MobileNet

This project implements real-time object detection using **OpenCV's DNN module** and the **SSD MobileNet v3 model**. The model detects objects from the **COCO dataset**.


## 📌 Features
- Uses **SSD MobileNet v3** for real-time object detection.
- Displays detected objects with confidence scores.
- Uses OpenCV to process video frames from the webcam.


## 📂 File Structure
📂 Object-Detection
├── 📄 coco.names                          # Class names from the COCO dataset
├── 📄 ssd_mobilenet_v3_large_coco_2020_01_14.pbtxt  # Model configuration file
├── 📄 frozen_inference_graph.pb           # Pre-trained model weights
├── 📝 object_detection.py                  # Main script for object detection
├── 📖 README.md                           # Project documentation


# Install Dependencies

Ensure you have Python installed, then install the required libraries:
pip install opencv-python numpy

##Run the Object Detection Script
python object_detection.ipynb

# #📋 Requirements


Python 3.x
OpenCV (cv2)
Pre-trained SSD MobileNet v3 model

 ## 📜 Model Files

Ensure the following files are in the project folder:
coco.names
ssd_mobilenet_v3_large_coco_2020_01_14.pbtxt
frozen_inference_graph.pb

 ## 🎥 How It Works

Starts the webcam and captures video.
Runs object detection using the SSD MobileNet v3 model.
Draws bounding boxes and labels around detected objects.
Displays live detection results in a pop-up window.
Press ‘q’ to exit or close the window.

 ## 📸 Example Output 
(Add an example image or video link here)

 ## 🛠 Future Improvements

Add custom model support for detecting specific objects.
Implement frame rate optimization for better performance.
Deploy as a web application for remote accessibility.


 ## 🤝 Contributing

Feel free to submit issues or pull requests.
For any queries, contact: onumiyal0@gmail.com

