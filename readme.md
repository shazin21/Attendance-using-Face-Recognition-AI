# Face Recognition Attendance System

## 📌 Project Description
This is a **Face Recognition-based Attendance System** that captures images of users, trains a model, and recognizes faces to mark attendance. It uses **OpenCV** for face detection and recognition, storing attendance in a CSV file.

---

## ⚡ Features
✅ Check Camera Functionality  
✅ Capture Images & Store Face Data  
✅ Train Faces for Recognition  
✅ Detect & Recognize Faces  
✅ Automatic Attendance Marking  
✅ CSV-based Attendance Records  

---

## 🛠 Tech Stack
- **Python**
- **OpenCV** (Face Detection & Recognition)
- **Pandas** (Attendance Data Handling)
- **NumPy** (Image Processing)
- **PIL (Pillow)** (Image Handling)

---

## 🚀 Installation
### 1️⃣ Clone the Repository
```sh
git clone https://github.com/YOUR_USERNAME/Face-Recognition-Attendance.git
cd Face-Recognition-Attendance
```

### 2️⃣ Install Dependencies
```sh
pip install opencv-python pandas pillow numpy
```

### 3️⃣ Run the Program
#### ✅ Check Camera
```sh
python check_camera.py
```
#### 📸 Capture Faces
```sh
python Capture_Image.py
```
#### 🎯 Train Model
```sh
python Train_Image.py
```
#### 🤖 Recognize & Mark Attendance
```sh
python Recognize.py
```
#### 🏠 Run with Main Menu
```sh
python Homepage.py
```

---

## 📂 Project Structure
```
Face-Recognition-Attendance/
│── haarcascade_frontalface_default.xml  # Face detection model
│── TrainingImage/                       # Captured face images
│── TrainingImageLabel/                   # Model file (Trainner.yml)
│── StudentDetails/                        # Student details CSV
│── Attendance/                            # Attendance records
│── check_camera.py
│── Capture_Image.py
│── Train_Image.py
│── Recognize.py
│── Homepage.py
│── README.md                              # Project documentation
│── .gitignore                              # Ignore unnecessary files
```

---

## 🎯 How It Works
1️⃣ **Check Camera** - Ensures the webcam is working.  
2️⃣ **Capture Faces** - Takes images and stores them in the dataset.  
3️⃣ **Train Model** - Uses OpenCV to train the face recognition model.  
4️⃣ **Recognize Faces** - Detects faces and marks attendance in a CSV file.  

---

## 📌 Notes
- Press `q` to exit the webcam view.
- The face dataset is stored in the `TrainingImage/` folder.
- Attendance records are saved in the `Attendance/` folder.\

---

## 📜 License
This project is **open-source** and free to use. Contributions are welcome! 🚀

