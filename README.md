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
```

### 2. Create and Activate a Virtual Environment

#### Windows:

```bash
python -m venv env
env\Scripts\activate
```

#### Linux/Mac:

```bash
python3 -m venv env
source env/bin/activate
```

### 3. Install Required Dependencies

```bash
pip install -r requirements.txt
```

---

## 🚀 Usage

### 🖥️ Run Gesture Recognition

To start the gesture recognition using your camera:

```bash
python gesture_recognition.py
```

The output video will be saved as:

```
gesture_output.mp4
```

---

## 🔍 How It Works

### 🧠 Gesture Classification Logic

- Uses **MediaPipe** to detect hand landmarks in real time.
- Applies logical conditions based on the relative position of fingers and thumb for each gesture:
  - **Thumbs Up** → Thumb up, all other fingers folded.
  - **Thumbs Down** → Thumb down, others folded.
  - **Fist** → All fingers folded.

### 🎥 Video Recording

- The video is encoded using **H.264**, offering:
  - Smooth FPS  
  - High compatibility  
  - Small file size

---

## 📸 Demo

✅ Real-time detection of gestures with live feedback:  
(Include GIF or image demo here)

---

## 🙌 Applications

- 🤖 AI-powered **gesture control systems**  
- 🏠 **Smart home automation**  
- 🧏‍♂️ **Sign language recognition**  
- 🎮 **Touchless interfaces** and **VR/AR experiences**

---

## 🙏 Acknowledgments

- **MediaPipe** → For powerful hand tracking APIs.  
- **OpenCV** → For real-time video processing and rendering.  
- **NumPy** → For efficient computation and logic.

---

## 🔗 Project Links

- 🔥 GitHub: https://github.com/Armanlaliwala/Real-Time-Hand-Gesture-Recognition-Using-MediaPipe-OpenCV  
- 📢 LinkedIn Post: https://www.linkedin.com/posts/armanlaliwala_ai-machinelearning-artificialintelligence-activity-7311607183916384256-cp9m

---

## 🤝 Contribute & Support

If this project helped you or sparked inspiration:  
⭐ Star the repo  
🍴 Fork it  
💬 Share your ideas or suggestions!

---

## 👨‍💻 About Me

I’m **Arman Laliwala**, a final-year Computer Engineering student passionate about **AI/ML**, building intelligent solutions for a better tomorrow.  
🛠️ Looking for collaborations on **AI/ML projects**? Let’s connect!

---

## 📬 Let’s Connect

🔗 YouTube: https://www.youtube.com/@armanlaliwala
🔗 GitHub: https://github.com/armanlaliwala
🔗 LinkedIn: https://www.linkedin.com/in/armanlaliwala/
🔗 Instagram: https://www.instagram.com/armanlaliwala
🔗 Medium: https://medium.com/@armanlaliwala
🔗 Kaggle: https://www.kaggle.com/armanlaliwala

---

## 📢 Hashtags

#AI #MachineLearning #ArtificialIntelligence #DataScience #Python #GestureRecognition #OpenCV #MediaPipe #SmartHome #SignLanguage #VR #AR #HumanComputerInteraction  
#armanlaliwala #laliwala #arman #ArmanLaliwala
