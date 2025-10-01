# 👷‍♂️ PPE Detection for Construction Site Safety
This project is a real-time Personal Protective Equipment (PPE) detection system designed to enhance worker safety on construction sites. It uses a custom-trained YOLOv8 model to identify whether workers are wearing essential safety gear, such as hardhats, safety vests, and masks.

The system processes video streams from either a live webcam or a pre-recorded file, drawing color-coded bounding boxes around detected individuals and objects. This provides immediate visual feedback on compliance with safety protocols.

<p align="center">
  <img src="https://github.com/user-attachments/assets/57b58e7e-42aa-44aa-a4f5-ce47bec8491c" alt="unknown_2025 09 29-14 57-ezgif com-optimize">
</p>


##  Features
Real-Time Detection: Analyzes video feeds to identify PPE compliance in real-time.

Custom YOLOv8 Model: Utilizes a powerful, custom-trained model (ppe.pt) for accurate detection.

Compliance Verification: Detects both the presence of required PPE (Hardhat, Safety Vest, Mask) and its absence (NO-Hardhat, etc.).

Intuitive Visual Feedback:

✅ Green Box: Indicates a worker is wearing the required PPE.

❌ Red Box: Warns that a worker is not wearing the required PPE.

🌸 Pink Box: Identifies other relevant objects on site (e.g., machinery, vehicles).

Flexible Input: Supports both live webcam streams and pre-recorded video files.

## 🛠️ Technology Stack
Python: Main programming language.

OpenCV (cv2): Video management, masking, and visualization.

Ultralytics YOLO: Framework for object detection (YOLOv8n).

cvzone: Used to simplify the display of rectangles and text.
