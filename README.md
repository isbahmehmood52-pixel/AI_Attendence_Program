# AI_Attendence_Program
📷 AI Attendance System

An automated facial recognition-based attendance tracking system built with Python and OpenCV. This project eliminates manual attendance taking by detecting and identifying faces in real-time or from images/video streams, automatically recording logs with timestamps.

✨ Features

👤 Real-Time Face Recognition: Detects and recognizes registered individuals instantly.

⏱️ Automated Logging: Saves attendance logs (Name, Date, Time) into CSV / Excel files automatically.

🚫 Duplicate Prevention: Prevents marking duplicate attendance for the same person in a single session.

⚡ Fast & Efficient: Uses optimized computer vision algorithms for fast detection.

🛠️ Built With

Python 3.x

OpenCV (opencv-python) - Real-time computer vision & video processing.

Face Recognition (face_recognition) - Deep learning face recognition library.

NumPy - Array and matrix manipulation.

Pandas (Optional) - Attendance data handling and CSV/Excel output.

🚀 Getting Started

Prerequisites

Make sure you have Python 3.8+ installed. Check your version with:

python --version


Installation

Clone the repository:

git clone https://github.com/YOUR-USERNAME/AI_Attendance_Program.git
cd AI_Attendance_Program


Install required dependencies:

pip install opencv-python face-recognition numpy pandas


Run the program:

python main.py


(Replace main.py with your entry file name).

🕹️ How It Works

Add known faces/images of individuals into your training folder.

Run the script to start your webcam or process a video stream.

The system scans incoming frames, matches faces with the database, and marks attendance with a timestamp.
