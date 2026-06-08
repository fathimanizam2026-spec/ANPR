# Automatic Number Plate Recognition (ANPR)

## Project Overview
Automatic Number Plate Recognition (ANPR) is a computer vision system that detects vehicle number plates and extracts the registration number from images or videos.

The project uses YOLOv8 for number plate detection and EasyOCR/Tesseract OCR for text recognition.

## Features
- Detect number plates from images and videos
- Real-time vehicle number recognition
- OCR-based text extraction
- Bounding box visualization
- Save recognized vehicle numbers

## Technologies Used
- Python
- OpenCV
- YOLOv8
- EasyOCR / Tesseract OCR
- NumPy
- Pandas
- Matplotlib

## Project Workflow
1. Load image or video.
2. Detect number plate using YOLOv8.
3. Crop detected plate region.
4. Apply OCR on cropped plate.
5. Extract vehicle registration number.
6. Display and save results.

## Dataset
Indian Number Plate Dataset from Kaggle.

## Applications
- Smart Parking Systems
- Toll Collection
- Traffic Monitoring
- Vehicle Tracking
- Security and Surveillance

## Output
The system detects vehicle number plates and displays the recognized registration number.

## Future Enhancements
- Real-time CCTV integration
- Database storage
- Vehicle owner information lookup
- Parking automation system

## Author
Fathima J
