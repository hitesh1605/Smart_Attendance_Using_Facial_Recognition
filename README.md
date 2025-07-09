# Smart Attendance Using Facial Recognition 🎯

This project is a Python-based **Smart Attendance System** that uses **Facial Recognition** to automate and manage attendance securely and efficiently.
###📸 Execution Screenshots  
### 🎥 Face Capturing  
![Capture](assets/screenshots/0.png)

### 🧠 Face Encoding
![Encoding](assets/screenshots/1.png)

### 🔍 Face Recognition & Attendance
![Recognition](assets/screenshots/2.png)


## 📌 Features

- 🎥 Capture face images using a webcam
- 🧠 Encode and store facial features
- 🔍 Recognize faces in real-time
- 🗂 Record attendance automatically in a CSV file
- 🧾 Easy to use, lightweight, and no need for manual attendance

---

## 🚀 How It Works

1. **Image Capture (`capture_images.py`)**  
   Register a new person by capturing multiple face images via webcam.

2. **Face Encoding (`encode_faces.py`)**  
   Converts all captured images into numerical facial encodings and stores them using `dlib`.

3. **Face Recognition & Attendance (`recognize_faces.py`)**  
   Compares live webcam feed with known faces and marks attendance in `attendance.csv`.

---

## 🧰 Technologies Used

- Python 3.x
- OpenCV
- face-recognition
- dlib
- numpy
- pandas

---

## Project Structure
SmartAttendance/
│
├── attendance/
│   └── attendance.csv               # Stores marked attendance
│
├── dataset/
│   └── [name]/                      # Captured images of each person
│
├── encodings/
│   └── face_encodings.pkl          # Serialized face data
│
├── capture_images.py               # Script to capture face images
├── encode_faces.py                 # Script to encode faces
├── recognize_faces.py              # Script to recognize and mark attendance
└── README.md                       # You're here :)
##🧑‍💻 Author  
-Hitesh Choudhary  
gmail:sirvihitesh8@gmail.com
