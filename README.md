# human-pose-detection
Human Pose Estimation using OpenCV and Streamlit
📌 Project Overview

This project is a Human Pose Estimation System developed using Python, OpenCV, TensorFlow, and Streamlit.

The application detects key body joints from an uploaded image and visualizes the human pose by drawing a skeletal structure over the person.

It uses a pretrained deep learning model (graph_opt.pb) with OpenCV’s DNN module to estimate body posture.

🚀 Features
Upload custom images
Detect human body keypoints
Draw skeleton structure on body
Adjustable confidence threshold
Streamlit-based web interface
Real-time pose visualization
🛠️ Technologies Used
Python
OpenCV
TensorFlow
Streamlit
NumPy
Pillow (PIL)
📂 Project Structure
human-pose-estimation/
│
├── estimation_app.py
├── graph_opt.pb
├── stand.jpg
├── README.md
├── requirements.txt
└── venv/
⚙️ Installation
1. Clone the Repository
git clone <repository_link>

OR download the ZIP file and extract it.

2. Open Project Folder
cd human-pose-estimation
3. Create Virtual Environment
python -m venv venv
4. Activate Virtual Environment
Windows
venv\Scripts\activate
Linux / Mac
source venv/bin/activate
5. Install Dependencies
pip install streamlit pillow numpy opencv-python
▶️ Run the Project

Run the Streamlit application:

streamlit run estimation_app.py

OR

python -m streamlit run estimation_app.py
🌐 Output

After running the command, open:

http://localhost:8501

in your browser.

📸 Working
Upload an image
The model processes the image
Body joints are detected
Skeleton structure is drawn
Output image is displayed
🧠 How It Works

The system uses:

OpenCV DNN module
TensorFlow pretrained pose estimation model
Heatmap-based keypoint detection

The model predicts:

Nose
Neck
Shoulders
Elbows
Wrists
Hips
Knees
Ankles
Eyes and Ears

These points are connected using predefined body pairs to generate the human skeleton.

📌 Applications
Fitness posture analysis
Yoga pose detection
Sports analytics
Motion tracking
Healthcare monitoring
Physical therapy
Gesture recognition
🔮 Future Enhancements
Real-time webcam detection
Exercise repetition counter
Posture correction system
AI fitness trainer
Multi-person pose estimation
Video pose tracking
📷 Sample Output

The application detects body joints and visualizes the pose skeleton on the uploaded image.

👨‍💻 Author

Developed by: Manaswi Sagiraju

📄 License

This project is for educational and learning purposes.
