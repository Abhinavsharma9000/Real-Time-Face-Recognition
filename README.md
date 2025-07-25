🧠Real-Time Face Recognition using OpenCV & KNN
Welcome to the Real-Time Face Recognition System – a lightweight, real-time computer vision project built using OpenCV and the K-Nearest Neighbors (KNN) algorithm. 
This project enables face detection and recognition directly from a live webcam feed — no deep learning required!

It captures face data, stores it efficiently, and uses KNN for recognizing individuals in real time.

*******************************************************************************************************************************************************************
🚀 Features
🎥 Real-Time Face Detection & Recognition via webcam

🧬 Face Data Collection & Labeling (saved as .npy files)

🧠 KNN Algorithm for classification (simple, fast, and effective)

🖼️ Haarcascade Classifier for efficient face detection

⚡ Minimal Dependencies – Easy to understand and deploy

******************************************************************************************************************************************************************

📁 Project Structure
bash
Copy
Edit
📦 Face-Recognition/
├── face_data_collect.py              # Capture and store face data
├── face_recognition.py              # Real-time face recognition using KNN
├── data/                            # Stores collected face data (.npy files)
├── haarcascade_frontalface_alt.xml  # Haar cascade model for face detection
└── README.md                        # Project documentation

******************************************************************************************************************************************************************

📸 How It Works
Collect face data using face_data_collect.py, which captures images from your webcam and saves them as .npy arrays.

Organize data in the data/ folder. Each file should correspond to a unique individual.

Run face recognition with face_recognition.py, which:

Accesses your webcam feed

Detects faces using the Haar cascade

Loads stored .npy training data

Uses KNN to find the closest match

Displays live video with bounding boxes and predicted names

******************************************************************************************************************************************************************

✅ Requirements
Python 3.x

OpenCV (cv2)

NumPy
