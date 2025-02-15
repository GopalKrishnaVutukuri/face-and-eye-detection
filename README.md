
# 👀 Face & Eye Detection using OpenCV

## 📖 Overview
This project implements **real-time face and eye detection** using **OpenCV** and **Haar Cascade classifiers**. It can detect **faces and eyes in images, videos, or live webcam streams** using pre-trained models.

## 🚀 Features
- Detects **faces** and **eyes** using Haar Cascade models.
- Works on **images, video files, and live webcam streams**.
- Draws **bounding boxes** around detected faces and eyes.
- Lightweight and fast detection with **OpenCV**.

## 🛠️ Technologies Used
- **Python** 🐍
- **OpenCV** 👀 (for image processing)
- **NumPy** 🔢 (for handling image arrays)

## 📂 Project Structure
```
📁 Face-Eye-Detection
│── 📄 face_eye_detection.ipynb   # Jupyter Notebook for detection
│── 📄 haarcascade_frontalface.xml  # Pre-trained face detection model
│── 📄 haarcascade_eye.xml          # Pre-trained eye detection model
│── 📂 images                      # Folder for test images
│── 📄 README.md                    # Project documentation (this file)
```

## 🔧 Installation & Setup

### **1️⃣ Install Dependencies**
Make sure you have **Python 3.7+** installed, then install OpenCV:

```bash
pip install opencv-python numpy
```

### **2️⃣ Clone the Repository**
```bash
git clone https://github.com/your-username/face-eye-detection.git
cd face-eye-detection
```

### **3️⃣ Run the Project**
#### ✅ **Jupyter Notebook (Recommended)**
```bash
jupyter notebook
```
Then open **face_eye_detection.ipynb** and run the cells.

#### ✅ **Python Script (If converted to `.py`)**
```bash
python face_eye_detection.py
```

---

## 🖱️ How to Use
1. **Run the script or Jupyter Notebook.**
2. **Upload an image** or start the **live webcam feed**.
3. The system will **detect faces and eyes** and **draw bounding boxes**.
4. **Press `ESC` to exit** the webcam mode.

---


## 📝 To-Do / Future Enhancements
- [ ] **Enhance face detection with Deep Learning (DNN)** 🧠  
- [ ] **Improve accuracy using DLIB or Mediapipe** 📈  
- [ ] **Add emotion recognition** 🎭  

---

## 👏 Acknowledgments
- **OpenCV** for providing pre-trained Haar Cascade models.
- **Various research papers** for improvements in face detection.

---

## 📜 License
This project is **open-source** under the **MIT License**. Feel free to use, modify, and share! 🚀  

---

