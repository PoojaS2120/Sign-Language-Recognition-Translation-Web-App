🖐️💻 Sign Language Recognition & Translation Web App

 📖 Overview
A Django-based web application for real-time sign language recognition and translation.  
Utilizes computer vision (Media Pipe, OpenCV) and deep learning (TensorFlow/Keras)  
to enable users to add new signs, train models, and translate between sign language and text.

---

🧰 Setup & Prerequisites

1️⃣ Python Version  
- Python 3.8 or higher is recommended.

🖐️💻 Sign Language Recognition & Translation Web App
📖 Overview

A Django-based web application for real-time sign language recognition and translation.
Utilizes computer vision (MediaPipe, OpenCV) and deep learning (TensorFlow/Keras)
to enable users to add new signs, train models, and translate between sign language and text.

🧰 Setup & Prerequisites
1️⃣ Python Version

Python 3.8 or higher is recommended.

2️⃣ Clone the Repository
git clone https://github.com/PoojaS2120/Sign-Language-Recognition-Translation-Web-App.git
cd Sign-Language-Recognition-Translation-Web-App

3️⃣ Create & Activate Virtual Environment (Recommended)

On Windows:

python -m venv venv
venv\Scripts\activate


On Linux/macOS:

source venv/bin/activate

4️⃣ Install Dependencies

All required libraries are listed in requirements.txt.

pip install -r requirements.txt

5️⃣ Tech Stack

See techstack.txt for a full list of technologies used.

🧠 Model Training (First Time Setup)

No pre-trained model is included.
To create and train your own sign language recognition model:

python app/training.py


➡️ This script will process your dataset and generate:
Dataset/sign_language_model.h5

🚀 Run the Project

Start the Django development server:

python manage.py runserver


➡️ Access the web app at:
http://localhost:8000

📂 Project Structure
Folder/File	Description
app/	Django app with views, models, and ML scripts
Dataset/	Stores sign images, label mappings, and trained model
media/	Uploaded images and generated videos
static/	Static files (CSS, JS, images)
templates/	HTML templates
requirements.txt	Python dependencies
techstack.txt	Technology stack details
⚡ Key Features

🔐 User authentication (register/login)

✋ Add new signs with webcam capture

🧠 Train and retrain sign recognition model

⌨️ Real-time sign-to-text prediction

🔄 Text-to-sign translation (images/videos)

🧩 Extensible dataset for new signs

📜 License

This project is licensed under the GNU General Public License v3.0.

© 2025 Pooja Gavit
This software is open-source and free to use under the terms of the license.

🧑‍💻 Developer Notes

Using a virtual environment is recommended for isolation.

For video features, ensure you have opencv-python installed.

For hand detection, install mediapipe.

For deep learning, install tensorflow and keras.

⚙️ Quick Start
# Clone, create virtual environment, install dependencies, train model, and run server
git clone https://github.com/PoojaS2120/Sign-Language-Recognition-Translation-Web-App.git
cd Sign-Language-Recognition-Translation-Web-App
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python app/training.py
python manage.py runserver