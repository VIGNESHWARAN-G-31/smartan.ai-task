# 🏋️ AI-Powered Exercise Pose Correction System

A real-time posture evaluation and repetition counter for fitness exercises using **MediaPipe**, **OpenCV**, and **Python**. The system analyzes body movements and provides feedback for form correction and rep counting using geometric analysis.

## 📽️ Demo Video & Outputs

🎥 Check all recorded exercise feedback videos and screenshots in the [Google Drive Output Folder](https://drive.google.com/drive/u/0/folders/1y_KiJy0xEEv1PO_oFlzLSNOz7F5B7nVw)

---

## ✅ Key Features

- 🔍 Detects pose landmarks using MediaPipe
- 🔁 Repetition counter with up/down movement logic
- 🧠 Real-time feedback for form corrections
- 🔧 Supports both **recorded video input** and **live webcam**
- 🖼️ Feedback box overlay showing:
  - Exercise name
  - Rep counts (left/right)
  - Elbow/shoulder/knee angles
  - Encouragement or correction messages

---

## 🧪 Supported Exercises

1. 💪 **Bicep Curls**
2. 🤸 **Lateral Raises**
3. 🧎 **Push-Ups**
4. 🦵 **Lunges**

---

## 📂 Folder Structure
├── main.py # Real-time / video input runner
├── exercises/
│ ├── bicep_curl.py # Bicep curl logic
│ ├── lateral_raise.py # Lateral raise logic
│ ├── lunge.py # Lunge logic
│ ├── pushup.py # Push-up logic
│ └── init.py
├── utils/
│ ├── pose_extractor.py # Keypoint extraction + drawing
│ ├── feedback_drawer.py # Draws rep count, angle, feedback
│ └── pose_utils.py # Angle calculation logic
├── videos/
│ ├── input/ # Input demo videos
│ └── output.mp4 # Output with visual feedback
├── requirements.txt
└── README.md

