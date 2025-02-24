# Facial Emotion Detection

This project implements a **Facial Emotion Detection** system using **OpenCV, Keras, and a pre-trained deep learning model**. The model detects facial expressions from a webcam feed and classifies them into different emotions.

## Features
- Real-time face detection using **Haar cascades**
- Emotion classification using a **deep learning model** trained on facial expression datasets
- Displays detected emotions on live video feed

## Prerequisites
Before running the project, ensure you have the following installed:
- Python 3.x
- OpenCV (`cv2`)
- TensorFlow/Keras
- NumPy
- Matplotlib

You can install the required dependencies using:

```bash
pip install opencv-python numpy tensorflow keras matplotlib
Model
The project uses a pre-trained deep learning model (best_model.h5).
The model predicts seven emotions:
Angry 😠
Disgust 🤢
Fear 😨
Happy 😊
Sad 😢
Surprise 😲
Neutral 😐
File Structure
bash
Copy
Edit
├── Emotion_Detection.ipynb  # Jupyter Notebook for model testing and visualization
├── best_model.h5            # Pre-trained deep learning model
├── haarcascade_frontalface_default.xml  # Face detection model
├── main.py                  # Python script for real-time emotion detection
└── README.md                # Project documentation
How to Run
Clone the repository:
bash
Copy
Edit
git clone https://github.com/your-username/emotion-detection.git
cd emotion-detection
Ensure best_model.h5 is present in the project directory.
Run the real-time emotion detection script:
bash
Copy
Edit
python main.py
Press q to quit the video feed.
Acknowledgments
The Haar cascade classifier for face detection is from OpenCV.
The model is trained on a facial expression dataset.
