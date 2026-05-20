# Human Pose Detection

Human Pose Estimation project built using **Python, OpenCV, TensorFlow, and Streamlit**.

This application detects human body keypoints from an uploaded image and visualizes the pose by drawing a skeletal structure.

---

## 🚀 Features

- Upload custom images
- Detect body keypoints
- Skeleton visualization
- Adjustable confidence threshold
- Streamlit web interface

---

## 🛠️ Technologies Used

- Python
- OpenCV
- TensorFlow
- Streamlit
- NumPy
- Pillow (PIL)

---

## 📂 Project Structure

```text
human-pose-estimation/
│
├── estimation_app.py
├── graph_opt.pb
├── stand.jpg
├── README.md
└── requirements.txt
```
## ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone <repository_link>
```

### 2️⃣ Open Project Folder

```bash
cd human-pose-estimation
```

### 3️⃣ Create Virtual Environment

```bash
python -m venv venv
```

### 4️⃣ Activate Virtual Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Linux / Mac

```bash
source venv/bin/activate
```

### 5️⃣ Install Dependencies

```bash
pip install streamlit pillow numpy opencv-python
```

---

## ▶️ Run the Project

```bash
streamlit run estimation_app.py
```

OR

```bash
python -m streamlit run estimation_app.py
```

Open in browser:

```text
http://localhost:8501
```

---
## 🧠 How It Works

1. Upload an image  
2. The model detects body joints  
3. Keypoints are connected to form a skeleton  
4. Output image is displayed  

The project uses **OpenCV DNN** with a pretrained TensorFlow model (`graph_opt.pb`) for pose estimation.

---

## 📌 Applications

- Fitness posture analysis
- Yoga pose detection
- Sports analytics
- Motion tracking
- Healthcare monitoring

---

## 🔮 Future Enhancements

- Real-time webcam detection
- Exercise repetition counter
- Posture correction system
- Multi-person pose estimation

---

## 👨‍💻 Author

**Manaswi Sagiraju**
