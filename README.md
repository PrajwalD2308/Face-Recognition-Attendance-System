# 🧠 Face Recognition Attendance System

An automated attendance system using Python, OpenCV, and MySQL that detects and recognizes faces in real-time to mark attendance securely and efficiently.

---

## 📌 Features

- 🎥 Real-time face detection and recognition using OpenCV
- 🗂️ Student/user registration with face data capture
- ✅ Automatic attendance marking
- 🧾 Attendance records stored in MySQL database
- 🖥️ User-friendly GUI (Tkinter or Flask-based)
- 🔒 Secure and reliable recognition system

---

## 🛠️ Tech Stack

- **Python** – Core programming language  
- **OpenCV** – Face detection and recognition  
- **NumPy** – Image data processing  
- **MySQL** – Attendance data storage  
- **Tkinter** – GUI (or Flask if web-based)

---

## 📸 How It Works

1. **Register Face**: Capture images of a person to train the model.
2. **Train Model**: Encoded faces are stored and associated with IDs/names.
3. **Recognize & Mark Attendance**: Recognizes faces from webcam and stores attendance with timestamp.
4. **View Records**: Attendance can be fetched from the MySQL database.

---
## 📸 Screenshots




## 🚀 Installation

### Prerequisites

- Python 3.x
- MySQL server (e.g., XAMPP / WAMP / MySQL Workbench)

1. Clone the repository to your local machine. ``` git clone https://github.com/Arijit1080/Face-Recognition-Based-Attendance-System ```
2. Install the required packages using ```pip install -r requirements.txt```.
3. Download the dlib models from ````https://drive.google.com/drive/folders/12It2jeNQOxwStBxtagL1vvIJokoz-DL4?usp=sharing and place the data folder inside the repo

## Usage

1. Collect the Faces Dataset by running ``` python get_faces_from_camera_tkinter.py``` .
2. Convert the dataset into ```python features_extraction_to_csv.py```.
3. To take the attendance run ```python attendance_taker.py``` .
4. Check the Database by ```python app.py```.


## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue if you find any bugs or have any suggestions.


