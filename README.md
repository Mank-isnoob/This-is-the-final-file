# Medi-Arm

Medi-Arm is a study project developed as part of my final year under the guidance of **Dr. Avinash Gautam** at **BITS Pilani**. The project involves building a robotic arm system aimed at automating medication dispensing and patient interaction.

## Project Overview

The **Medi-Arm** project focuses on leveraging **computer vision** and **OCR technologies** to detect and interpret prescription labels for accurate medication dispensing. The robotic arm is integrated with a mobile application to provide features like remote monitoring and real-time medication adjustments.

### Key Features
- **Robust Detection**: Uses the YOLO model for identifying medicine bottles and relevant labels.
- **OCR Integration**: Incorporates Vision Language Models (VLMs) for text recognition on labels.
- **App Integration**: Links with a mobile app for remote interaction, allowing caregivers to manage prescriptions seamlessly.
- **User-Friendly Design**: Simplified operations with minimal manual input.

## Dataset
The project utilizes a **custom dataset** specifically designed for detecting and identifying prescription labels on medicine bottles. The dataset includes labeled images of varying conditions to ensure robust performance in real-world scenarios.

### Access the Dataset
The custom dataset can be accessed via [this link](https://universe.roboflow.com/dataset-urrjn/dataset1-czkg7/browse?queryText=&pageSize=50&startingIndex=0&browseQuery=true).

## Technology Stack
- **Computer Vision**: YOLO-based model trained using PyTorch.
- **OCR and Text Recognition**: Vision Language Models (VLMs).
- **Mobile App Development**: Flutter framework for app design and integration.
- **Hardware Integration**: Custom robotic arm for physical dispensing.
- **Backend**: Python-based processing pipeline for image recognition and command generation.

## How It Works
1. **Prescription Input**: The system processes input from a prescription document.
2. **Detection and OCR**: Identifies medicine bottles and extracts relevant label details using YOLO and VLM.
3. **Medication Dispensing**: The robotic arm picks and dispenses the correct medication.
4. **App Interaction**: Real-time updates are provided to the caregiver through the integrated mobile app.

## Contributions
- Developed the detection pipeline using **YOLO** for identifying medicine bottles.
- Implemented OCR functionality with **Vision Language Models** for text extraction.
- Collaborated with team members to integrate robotic arm functionality with a mobile app.

## Acknowledgements
This project was made possible through the support of **Dr. Avinash Gautam** and the resources provided by **BITS Pilani**.

---

Feel free to clone this repository and explore the code. If you have any questions or suggestions, feel free to raise an issue or reach out.

---
