# 🎞️ FrameFlipCV – Reverse Video Using OpenCV

FrameFlipCV is a simple **Computer Vision project** built with **Python and OpenCV** that reverses a video by extracting its frames, storing them, and then displaying them in reverse order.

This project demonstrates **frame-level video processing**, resizing, saving frames, and reverse playback — making it ideal for **AI & CV students**.

---

## 🚀 Project Overview

The workflow of this project is:
1. Read a video file using OpenCV  
2. Extract and save each frame as an image  
3. Store frame paths in a list  
4. Reverse the list  
5. Display frames in reverse order to simulate video reversal  

---

## 🛠️ Technologies Used
- **Python**
- **OpenCV (cv2)**

---

## 🧠 How the Code Works

### 🔹 Step 1: Capture Video
The video is loaded using `cv2.VideoCapture()`.

### 🔹 Step 2: Frame Extraction
Each frame is:
- Read from the video
- Resized to `320 × 240`
- Saved as a `.jpg` image
- Stored in a list for later use

### 🔹 Step 3: Reverse Playback
The frame list is reversed using Python’s `reverse()` function, and frames are displayed sequentially to create a reversed video effect.

---

## ▶️ How to Run the Project

### 1️⃣ Clone the Repository
```
git clone https://github.com/ZahraBatool2024/FrameFlipCV.git
cd FrameFlipCV
```
### 2️⃣ Install Dependencies

- Python

- OpenCV

### 3️⃣ Run the Script
```
python reverse_video.py
```
### 4️⃣ Controls

Press **q** to quit video playback

----

## 📌 Example Use Cases

- Video editing basics

- Learning frame-level video processing

- Computer vision practice

- Academic CV projects

## 🌟 Future Improvements

- GUI interface

- Support for different video formats

- Add audio reversal

- Optimize performance for large videos



