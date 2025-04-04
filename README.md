# ✋ Real-Time Hand Gesture Recognition Using MediaPipe & OpenCV

![Python](https://img.shields.io/badge/Python-3.8%2B-blue) ![OpenCV](https://img.shields.io/badge/OpenCV-4.5%2B-green) ![MediaPipe](https://img.shields.io/badge/MediaPipe-0.9%2B-orange)

## 🚀 Project Overview

This project uses **MediaPipe** and **OpenCV** to recognize **hand gestures in real-time** from a live camera feed.  
It supports the detection of predefined gestures including:

- 👍 **Thumbs Up**
- 👎 **Thumbs Down**
- ✊ **Fist**

The system:
- 🎯 Detects and classifies hand gestures using landmarks.
- 🎥 Saves the processed video feed using the **H.264 codec** for smooth playback and wide compatibility.
- 🧠 Can be integrated into applications such as **touchless interfaces**, **smart homes**, and **gesture-controlled systems**.

---

## ⚙️ Features

✅ Real-time gesture recognition using webcam input.  
✅ Detects gestures: **Thumbs Up**, **Thumbs Down**, and **Fist**.  
✅ Saves annotated output video with high-quality encoding.  
✅ Clean and extensible codebase to add more gestures.  
✅ Supports **external cameras** (e.g., mobile camera via DroidCam/Iriun).

---

## 🛠️ Tech Stack

- **Language:** Python  
- **Libraries:**  
  - `MediaPipe` → For hand landmark tracking.  
  - `OpenCV` → For video capture, drawing, and output.  
  - `NumPy` → For gesture logic and classification.

---

## 📝 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Armanlaliwala/Real-Time-Hand-Gesture-Recognition-Using-MediaPipe-OpenCV.git
cd Real-Time-Hand-Gesture-Recognition-Using-MediaPipe-OpenCV
