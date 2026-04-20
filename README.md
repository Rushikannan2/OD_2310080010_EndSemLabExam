🚗 Smart Parking Detection System
📌 Overview

This project implements a Smart Parking Detection System using Computer Vision techniques.
It processes parking images, detects vehicles, visualizes parking slots, and evaluates performance under different conditions.

🎯 Objectives
Preprocess parking images
Detect vehicles using HOG + Sliding Window
Visualize parking slots using bounding boxes
Implement object detection (SSD/YOLO concept)
Evaluate using IoU and Precision
Analyze performance under lighting variations
🗂️ Dataset

Images Used:

park1.jpg
park2.jpg
park3.jpg

Path:

/content/drive/MyDrive/OD_EndSemLab/
⚙️ Technologies Used
Python
OpenCV
NumPy
Matplotlib
🔧 Implementation
1. Image Preprocessing
Grayscale conversion
Gaussian / Median filtering
Thresholding
2. Vehicle Detection
HOG (Histogram of Oriented Gradients)
Sliding Window approach
Bounding box detection
3. Parking Slot Visualization
Manual slot coordinates
Rectangle drawing using OpenCV
4. Object Detection (SSD Concept)
Lightweight detection using OpenCV
Bounding boxes for vehicles
5. Evaluation Metrics
IoU (Intersection over Union)
Precision
6. Performance Analysis
Tested under:
Bright lighting
Dark lighting

Observation:

Bright → better detection
Dark → reduced accuracy
📊 Results
Vehicles detected using sliding window
Parking slots visualized successfully
Detection varies with lighting conditions
🧠 Key Learnings
Importance of preprocessing
Role of feature extraction (HOG)
Limitations of traditional methods
Need for deep learning (YOLO/SSD)
🚀 Future Improvements
Use YOLOv5 / YOLOv8 for better accuracy
Real-time parking monitoring
Integration with IoT sensors
Automatic empty slot detection
📌 Conclusion

This project demonstrates how Computer Vision techniques can be applied to parking detection.
Basic methods work, but deep learning models significantly improve accuracy.

👨‍💻 Author

Rushi Kannan
