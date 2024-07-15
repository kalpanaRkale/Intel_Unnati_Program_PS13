# Intel_Unnati_Program_PS13

Team Name - NeuralNet Wizards

# Automated Vehicle Movement Analysis and Insight Generation using Edge AI

yeh chalega..

# Problem Statement
PS13 - “Vehicle Movement Analysis and Insight Generation in a College Campus using Edge AI”.
As college campuses grow in size and population, managing vehicle movement becomes increasingly challenging. Traditional manual methods of monitoring vehicles are inefficient and prone to errors. There is a pressing need for an automated solution to track, count, and analyze vehicle movement, ensuring effective management of parking spaces and improving overall campus security.

Efficiently managing vehicle movement, monitoring parking spaces, and ensuring security in large campuses or urban areas are significant challenges. Traditional methods are often inefficient, labor-intensive, and prone to errors. There is a need for an automated, real-time solution to track vehicle movement, count vehicles, estimate their speed, recognize number plates, and manage parking spaces effectively.

# Solution
Our solution employs advanced Edge AI cameras integrated with YOLOv10 for vehicle detection and EasyOCR for automatic number plate recognition (ANPR). Additionally, OpenCV Python is utilized for parking space counting and analysis. This comprehensive system provides real-time insights into vehicle movement, enhances security, and optimizes parking space management.


# Features
1. Vehicle Tracking and Counting: Monitors and counts vehicles entering and leaving the monitored area.
2. Speed Estimation: Calculates vehicle speed to ensure safety and regulation compliance.
3. Automatic Number Plate Recognition (ANPR): Utilizes YOLOv10 and EasyOCR for accurate number plate recognition.
4. Parking Space Counter: Uses OpenCV Python to monitor and manage parking space (open-space and closed space) availability.
5. Edge AI Processing: Ensures real-time data processing on the device, reducing latency and reliance on cloud services.

# Technologies Used

- YOLOv10: For real-time vehicle detection.
- EasyOCR: For number plate recognition.
- Edge AI Cameras: For on-device image capture and processing.
- OpenCV Python: For image processing and parking space counting.
- Python: For model implementation and system integration.

- Pretrained models used - 
  YOLOv10 Model (coco_model): A pretrained model for general object detection trained on the COCO dataset. The model identifies various objects in images or video frames efficiently.
  License Plate Detector (license_plate_detector): Specifically designed to locate and recognize license plates.This model used in Automatic License Plate Recognition (ALPR) systems for accurate plate identification.
  SORT Tracker (mot_tracker): An algorithm for real-time multi-object tracking. It ssigns unique IDs to objects across frames, enabling continuous tracking in video sequences.

