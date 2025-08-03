# faceDetection-
Real-Time Face Detection using OpenCV
This project uses OpenCV's Haar Cascade classifier to detect human faces in real-time via your webcam.

📸 Demo
When you run the script, your webcam will open, and blue rectangles will appear around detected faces. Press q to exit.

📁 Files
face_detection.py – Main Python script to perform real-time face detection.

No external dataset needed – uses OpenCV’s built-in Haar Cascade.

🛠️ Requirements
Python 3.x

OpenCV

📦 Installation
Clone the repository and install OpenCV:

bash
Copy
Edit
git clone https://github.com/your-username/face-detection-opencv.git
cd face-detection-opencv
pip install opencv-python
▶️ Run the Code
bash
Copy
Edit
python face_detection.py
Make sure your webcam is connected and accessible.

🧠 How It Works
Uses Haar Cascade classifier:
haarcascade_frontalface_default.xml

Converts frame to grayscale for faster processing.

Detects faces with detectMultiScale.

Draws bounding boxes on detected faces.

🚀 Output
A real-time video feed with rectangles drawn around faces.

Press q to close the window.

🙌 Credits
OpenCV

Haar Cascade model provided by OpenCV

