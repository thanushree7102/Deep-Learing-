# Smart Waste Detection and Classification System using Deep Learning

## Project Overview

The Smart Waste Detection and Classification System is a Deep Learning project developed to automatically detect and classify waste into different categories such as **Wet Waste**, **Dry Waste**, and **Recyclable Waste**. The system uses object detection models to improve waste segregation and support smart waste management.

This project compares different deep learning models including **YOLOv5**, **YOLOv8**, and **Faster R-CNN** to identify the best-performing model for waste detection.

---

## Project Objectives

- Detect waste objects from images.
- Classify waste into:
  - Wet Waste
  - Dry Waste
  - Recyclable Waste
- Compare the performance of multiple deep learning models.
- Improve waste segregation accuracy.

---

## Deep Learning Models Used

- YOLOv5
- YOLOv8
- Faster R-CNN

---

## Project Structure

```
Smart Waste Detection and Classification System
│
├── YOLOv5_Waste_Detection_Wet_Dry_Recycle.ipynb
├── YOLOv8_Waste_Detection_Wet_Dry_Recycle.ipynb
├── RCNN_waste_detection_wet_dry_recycle.ipynb
├── Comparison_model.ipynb
├── Project Report.pdf
├── Dataset Links.pdf
├── Presentation.pdf
└── README.md
```

---

## Dataset

The dataset contains images of different waste materials categorized into:

- Wet Waste
- Dry Waste
- Recyclable Waste

Dataset links are provided in:

```
DL_SMART WASTE DETECTION AND CLASSIFICATION SYSTEM_Thanushree.NH_dataset links.pdf
```

---

## Technologies Used

- Python
- Jupyter Notebook
- OpenCV
- NumPy
- Pandas
- Matplotlib
- PyTorch
- Ultralytics YOLO
- Faster R-CNN

---

## Installation

### Clone the repository

```bash
git clone <repository-link>
```

### Install dependencies

```bash
pip install ultralytics
pip install torch torchvision
pip install opencv-python
pip install pandas
pip install numpy
pip install matplotlib
pip install scikit-learn
pip install pillow
```

---

## Running the Project

### YOLOv8

Open:

```
YOLOv8_Waste_Detection_Wet_Dry_Recycle.ipynb
```

Run all notebook cells.

---

### YOLOv5

Open:

```
YOLOv5_Waste_Detection_Wet_Dry_Recycle.ipynb
```

Run all notebook cells.

---

### Faster R-CNN

Open:

```
RCNN_waste_detection_wet_dry_recycle.ipynb
```

Run all notebook cells.

---

## Performance Comparison

The project compares:

- Detection Accuracy
- Precision
- Recall
- mAP (Mean Average Precision)
- Training Time
- Inference Time

The comparison is available in:

```
Comparison_model.ipynb
```

---

## Results

The trained models can:

- Detect waste objects in images.
- Draw bounding boxes around detected waste.
- Predict the waste category.
- Display confidence scores.

Among the evaluated models, **YOLOv8** demonstrated the best balance of detection accuracy and inference speed, making it suitable for real-time waste detection applications.

---

## Applications

- Smart Cities
- Waste Segregation
- Recycling Plants
- Smart Dustbins
- Environmental Monitoring
- Municipal Waste Management

---

## Future Scope

- Real-time webcam detection.
- Mobile application integration.
- IoT-enabled smart dustbins.
- Multi-class waste detection.
- Cloud deployment.

