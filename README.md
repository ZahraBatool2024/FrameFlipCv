<div align = "center">
  
# 🎞️ FrameFlipCV – Reverse Video Using OpenCV

</div>
FrameFlipCV is a simple **Computer Vision project** built with **Python and OpenCV** that reverses a video by extracting its frames, storing them, and then displaying them in reverse order.

This project demonstrates **frame-level video processing**, resizing, saving frames, and reverse playback — making it ideal for **AI & CV students**.

---
<div align = "center">
  
## 🚀 Project Overview
</div>
The workflow of this project is:
1. Read a video file using OpenCV  
2. Extract and save each frame as an image  
3. Store frame paths in a list  
4. Reverse the list  
5. Display frames in reverse order to simulate video reversal  

---
<div align = "center">
  
## 🛠️ Technologies Used
</div>

- **Python**
- **OpenCV (cv2)**

---
<div align = "center">
  
## 🧠 How the Code Works
</div>

### 🔹 Step 1: Capture Video

The video is loaded using `cv2.VideoCapture()`.

https://github.com/ZahraBatool2024/FrameFlipCv/blob/main/videoToBeReverse.mp4

### 🔹 Step 2: Frame Extraction

Each frame is:
- Read from the video
- Resized to `320 × 240`
- Saved as a `.jpg` image
- Stored in a list for later use

### 🔹 Step 3: Reverse Playback
The frame list is reversed using Python’s `reverse()` function, and frames are displayed sequentially to create a reversed video effect.

https://github.com/ZahraBatool2024/FrameFlipCv/blob/main/ReversedVideo.mp4

---
<div align = "center">
  
## ▶️ How to Run the Project
</div>

### 1️⃣ Clone the Repository
```
git clone https://github.com/ZahraBatool2024/FrameFlipCV.git
cd FrameFlipCV
```

### 2️⃣ Install Dependencies

- Python

- OpenCV

### 3️⃣ Run the Script

python videoReverse.py

### 4️⃣ Controls

Press **q** to quit video playback

----
<div align = "center">
  
## 📌 Example Use Cases
</div>

- Video editing basics

- Learning frame-level video processing

- Computer vision practice

- Academic CV projects
<div align = "center">
  
## 🌟 Future Improvements
</div>

- GUI interface

- Support for different video formats

- Add audio reversal

- Optimize performance for large videos

<div align="center">
  
## Contact & Contribution

Have feedback, want to collaborate, or just say hello?  
Let’s connect and build something useful together.

📧 **Email:** zahraishaq2004@gmail.com    
💻 [GitHub Repo](https://github.com/ZahraBatool2024/FrameFlipCv)

Found this project useful? Give it a **star** on GitHub.  
Want to improve it? Submit a **Pull Request** and contribute to enhancing this system.

Your ideas and contributions help improve this real-time AI system.
</div>

