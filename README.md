# Contactless_Ticket_Collecting_System

A Python-based contactless ticket collection system that uses real-time face recognition to identify users without physical interaction.

This project detects and recognizes faces from a camera feed and compares them to a set of stored reference images — making it suitable for automated entry systems like events, transport, or access control.

🧠 Features

✔ Real-time face detection & recognition
✔ Compare faces using multiple algorithms
✔ Simple Python implementation with OpenCV
✔ Supports webcam/video input

🚀 Project Structure
📦 Project-2
├── image_comparison.py        # Compare two images using face similarity
├── main_video.py              # Main real-time recognition loop
├── simple_facerec.py          # Simple face recognition helper
├── Messi1.webp                # Sample face image (reference)
├── URLs (links).url           # Resource links (tutorials/videos)
└── README.md

🛠️ Setup Instructions
📌 Requirements

Install the required Python packages:

pip install opencv-python
pip install face_recognition
pip install numpy


Note: Make sure your system has a webcam or a connected video camera.

▶ Running the Project
1. Run the real-time face recognition
python main_video.py


This will open the webcam feed and attempt to detect and recognize faces live.

2. Compare two face images
python image_comparison.py


This script takes two input images and computes how similar the faces are.

📍 How It Works

The system grabs images (either from camera or disk).

It detects faces using OpenCV and the face_recognition library.

Encodings from detected faces are compared with stored reference encodings.

If a match is found, the user is identified.

🧩 Libraries Used
Library	Purpose
OpenCV	Image/video stream handling
face_recognition	Face detection & recognition
NumPy	Numerical processing
📚 Resources & References

Links included in this repository are tutorials or guides (e.g., “face recognition in real time with OpenCV and Python”).

These can help you understand how the algorithms work and how to customize them further.

⭐ Future Enhancements

✅ Add UI to register new users
✅ Store recognized faces in a database
✅ Integrate with SMS/email notification
✅ Deployment as a web/mobile app

📜 License

This project is open-source and available for learning and enhancement.
