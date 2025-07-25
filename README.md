# YOLO-Project
# about the project:
This project uses deep learning (YOLOv8) to automatically detect motorbike riders violating traffic rules, specifically identifying those without helmets and those using camera-mounted helmets. Violators are further processed using OCR to detect number plates and categorize offenses for further action.it is done by creating a  custom dataset with real life photos

# Key Features:
Detects:
1.Riders without helmets

2.Riders with helmets

3.Riders with helmets + camera attached

Uses custom-trained dataset with real-life road images
OCR integration to extract and record vehicle number plates
Saves detected offenses into categorized folders
Exports violator data to CSV files after duplicate removal
Achieved 98% accuracy with high real-time precision

# Tools and Technologies Used:
YOLOv8 (Object Detection)
LabelImg (Data Annotation)
OpenCV (Image Processing)
OCR (Optical Character Recognition) – for license plate detection
Python – core programming
Custom Dataset – 1200+ real-world traffic images
CSV File Handling – for storing and filtering results

# Future Scope:
Integration with live CCTV feeds for real-time monitoring
Detection of other traffic rule violations (e.g., wrong-lane stopping, no signal halts)
Use of heat sensors and weather detection modules
Smart alert system for live offense reporting to traffic authorities
Deployment on embedded systems like Raspberry Pi for roadside use.
System is specifically trained to identify helmets only, indicating a better model than MVD cameras
