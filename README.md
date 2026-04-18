# 🎯 Face Detection & Recognition with Augmented Reality

Project developed within the course **Computer Vision and Mixed Reality**  
Master’s Degree in Computer Software and Media Applications Engineering – ISEL

---

## 📌 Description

This project consists of a computer vision application capable of:

- Detecting faces in real time
- Recognizing individuals based on a trained dataset
- Applying **Augmented Reality (AR)** elements on detected faces

The entire system is implemented in a **Jupyter Notebook**, combining face detection, recognition, and AR overlay in a single interactive pipeline.
---

## 🧠 Features

- ✅ Real-time face detection (MediaPipe)
- ✅ Facial landmarks extraction
- ✅ Face normalization (alignment, resize, grayscale)
- ✅ Face recognition using **LBPH (OpenCV)**
- ✅ Confidence-based classification
- ✅ Augmented Reality objects (glasses, hat, mustache)
- ✅ Interactive execution via notebook

---

## 🛠️ Technologies

- Python
- OpenCV
- MediaPipe
- NumPy
- Jupyter Notebook

---

## ⚙️ How it works

The system follows this pipeline:

1. Capture frame from webcam
2. Detect faces and extract landmarks
3. Normalize face
4. Perform face recognition (LBPH)
5. Apply AR object based on identity

---

## 📂 Project Structure
dataset/

├── train/

└── test/

images/

├── hat.png

├── sunglasses.png

└── mustache.png


landmarkers/

├── face_landmarker.task


TP1.ipynb

---

## ▶️ How to run

### 1. Clone the repository
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

### 2. Install dependencies
pip install opencv-python mediapipe numpy matplotlib notebook

### 3. Run the project

### How to train the model
To train the model you need to add a directory named after the person with their pictures in the directory dataset/train.
For example: 

dataset/

├── test/

└── train/

    └── tom_hanks
    
        ├── tom_hanks1.png
        
        └── tom_hanks2.png
        
        
### Author
Miguel Azenha
ISEL - Instituto Superior de Engenharia de Lisboa
