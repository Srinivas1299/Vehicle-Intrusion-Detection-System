# Vehicle-Intrusion-Detection-System
🚗 Vehicle Intrusion Detection System (VIDS)
Face Authentication + Number Plate Recognition using ML (XGBoost & SVM)

📌 Overview
Vehicle Intrusion Detection System (VIDS) is a security system that verifies vehicle access using Face Recognition and Number Plate Recognition. It uses:

Face Recognition with XGBoost to authenticate vehicle owners.
OCR (Optical Character Recognition) with SVM to extract and validate number plates.
OpenCV for image processing and Python for implementation.
🔹 Use Case: Enhancing security in parking lots, gated communities, and restricted areas.

🎯 Features
✅ Face Authentication – Recognizes vehicle owners using machine learning.
✅ Number Plate Recognition – Extracts and verifies vehicle numbers via OCR + SVM.
✅ Real-time Image Processing – Uses OpenCV for efficient face and plate detection.
✅ Database Storage – Stores owner details for future verification.
✅ Alerts for Unauthorized Access – Notifies on unregistered vehicle detection.

🛠 Tech Stack
🔹 Programming Language: Python 🐍
🔹 Libraries & Frameworks:

OpenCV (Face & Plate Detection)
XGBoost (Face Recognition)
SVM (Number Plate Classification)
Tesseract OCR (Character Recognition)


1️⃣ Data Collection
Face images and vehicle number plate images are captured and stored.
Face data is labeled with owner IDs.
Number plates are mapped to their respective owners.
2️⃣ Preprocessing
Images are converted to grayscale and resized.
Faces are detected using Haar cascades or DNN.
Number plates are localized using OpenCV edge detection.
3️⃣ Feature Extraction & Model Training
Face Recognition (XGBoost)
Face features extracted using OpenCV.
XGBoost model is trained for classification.
Number Plate Recognition (SVM & OCR)
OCR extracts characters from plates.
SVM classifies characters into digits/letters.
4️⃣ Classification & Authentication
Captured face images are matched with stored data.
Number plates are compared with the database.
If both match, access is granted; else, an alert is triggered.

