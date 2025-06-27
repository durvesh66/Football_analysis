# ⚽ Football Analysis System

A computer vision-based system for analyzing football videos using object detection (YOLOv8), video processing (OpenCV), and statistical analysis to understand gameplay dynamics and track player movement.

![GitHub Repo Size](https://img.shields.io/github/repo-size/durvesh66/Football_analysis)
![Last Commit](https://img.shields.io/github/last-commit/durvesh66/Football_analysis)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

---

## 🎯 Objective

The project processes football match videos to:
- Detect players and the ball in each frame
- Track objects across time
- Generate insights from video data
- Output a processed video with overlays

---

## 🧠 Features

- ✅ YOLOv8 integration for real-time object detection
- ✅ OpenCV-based frame processing and video handling
- ✅ Dynamic visual overlays showing player and ball positions
- ✅ Output rendered video with detections and tracking

---

## 🛠️ Tech Stack

- **Python 3.11+**
- [YOLOv8 (Ultralytics)](https://github.com/ultralytics/ultralytics)
- OpenCV
- NumPy
- Matplotlib (for future analytics)
- Pandas (if statistical logs are added)

---

## 📁 Project Structure

Football_analysis/
├── data/ # Input videos or frames
├── models/ # Trained models (best.pt not included)
├── output_videos/ # Processed video results
├── src/ # Core Python scripts
│ └── main.py # Main script for detection
├── all-files.txt # Internal large file listing
└── README.md # You're reading it!
2. Download YOLOv8 Weights
Upload your trained model best.pt (not included in this repo) to the models/ folder.

3. Run the Analysis
   python src/main.py --input data/input_video.mp4 --weights models/best.pt --output output_videos/output_video.avi
