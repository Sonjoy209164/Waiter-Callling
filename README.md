# 🧠 Waiter-Calling – AI-Based Desk and Hand Raise Detection

A computer vision project that detects when a person raises their hand in an office to request coffee. It uses OpenCV and color segmentation to identify desks from images or video feeds and leverages deep learning models to detect hand gestures, enabling an automated waiter-calling or seating system.

---

## 📹 Demo

[![Watch the demo](https://img.youtube.com/vi/NxLjAFeIc8g/0.jpg)](https://youtu.be/NxLjAFeIc8g)

> Click the image to watch the video demonstration on YouTube.

---

## 🧰 Technologies Used

- **Python** – Core programming language  
- **OpenCV (`cv2`)** – Image processing and computer vision  
- **NumPy** – Matrix operations and numerical computing  
- **Matplotlib** – Image display and visualization  
- **MediaPipe** – Real-time hand and body landmark detection  
- **Ultralytics YOLOv8** – Deep learning object detection  
- **gdown** – Downloading models from Google Drive  
- **Google Colab/Drive Integration** – For cloud-based execution and storage  
- **IPython Display** – Showing images and videos inside notebooks

---

## 💡 Features

1. **Desk Detection via Color Segmentation**  
   Detects green-colored desks from static images or video frames using HSV filtering.

2. **Hand Raise Detection**  
   Uses MediaPipe and YOLOv8 models to detect when a user raises a hand at their desk.

3. **Real-time Video Processing**  
   Processes videos in real time to track user activity.

4. **Visual Feedback**  
   Annotates detected hands and desks on video output for easy visualization.

5. **Interactive Notebook**  
   Easy-to-follow code in a Jupyter notebook (`Sonjoy_Waiter_c_sol.ipynb`), ideal for experimentation and demo purposes.

---

## 🛠️ How to Run

1. **Clone the repository**  
   ```bash
   git clone https://github.com/Sonjoy209164/Waiter-Callling.git
   cd Waiter-Callling
