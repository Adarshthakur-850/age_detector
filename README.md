 🧓 Age Detector Using Computer Vision

An intelligent computer vision project built with Python that detects **human faces** and **predicts the approximate age** of the person using a deep learning model. The project utilizes OpenCV for face detection and a pre-trained deep learning model to estimate age.

---

## 📌 Table of Contents

- [Features](#-features)
- [Demo](#-demo)
- [Tech Stack](#-tech-stack)
- [Installation](#-installation)
- [Usage](#-usage)
- [Project Structure](#-project-structure)
- [Screenshots](#-screenshots)
- [License](#-license)

---

## ✅ Features

- 📷 Real-time webcam input using OpenCV
- 🧠 Pre-trained deep learning model for age prediction
- 🧑 Accurate face detection with Haar cascades or DNN
- 🔁 Continuous frame processing (real-time)
- 💬 Age group predictions like `0–2`, `4–6`, `8–12`, ..., `60–100`

---

## 🎥 Demo

> Add a short video/GIF or link showing the real-time webcam demo.

---

## 🧰 Tech Stack

- **Language**: Python 3.x
- **Libraries**:
  - OpenCV
  - NumPy
  - Pre-trained Caffe Model (`age_net.caffemodel`)
- **Model**:
  - Age classification DNN from OpenCV Model Zoo

---

## 💻 Installation

```bash
git clone https://github.com/yourusername/Age_Detector.git
cd Age_Detector

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

pip install -r requirements.txt

python age_detector.py
🚀 Usage
Make sure you have a webcam connected.

Run the script: python age_detector.py

Allow camera permissions.

The app will detect a face and display the predicted age range.

📂 Project Structure
bash
Copy
Edit
Age_Detector/
├── age_detector.py              # Main script
├── README.md                    # Documentation
├── requirements.txt             # List of Python dependencies
├── models/
│   ├── age_deploy.prototxt      # Model architecture
│   └── age_net.caffemodel       # Pre-trained weights
├── assets/
│   └── screenshot.png           # Sample output images
📸 Screenshots

🧠 How It Works
Face Detection: Uses OpenCV's Haar Cascade or DNN face detector.

Age Estimation: Loads the Caffe model and predicts one of 8 age ranges:

0–2, 4–6, 8–12, 15–20, 25–32, 38–43, 48–53, 60–100

📜 License
This project is licensed under the MIT License.

🤝 Contributions
Pull requests are welcome. For major changes, open an issue first to discuss what you would like to change.

🙋‍♂️ Author
Adarsh Thakur
📧 thakuradarsh8368@gmail.com
🔗 GitHub Profile
