# 🧍 Intelligent Human Posture Detection System

This project uses a YOLO-based pose detection model to analyze human posture from images. It leverages the **Ultralytics YOLOv11** framework and **Gradio** for an interactive web interface. The system identifies key spinal points and evaluates posture quality using simple geometric heuristics.

## 🚀 Features

- 📸 Upload your own image or select an example (front or side view)
- 🧠 Analyze spine posture using a trained YOLO model
- 📈 Plot the spinal curve (spine profile) to visualize alignment
- 📏 Output a simple diagnostic based on spinal angles
- 🔁 Switch between different trained model versions

---

## 📦 Requirements

Make sure to install all required dependencies:

```bash
pip install ultralytics gradio opencv-python-headless matplotlib pillow
