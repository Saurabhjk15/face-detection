# Face Detection with Real-Time Database

## Overview 🏆
This project is a face detection system that utilizes real-time database integration to enhance security and authentication processes. It allows users to:
- Detect and recognize faces in real-time.
- Store encoded facial data in a database for future identification.
- Authenticate users based on image data.

The system employs computer vision and machine learning techniques to process facial features efficiently. With Firebase integration, it ensures fast and secure data storage, making it suitable for applications like attendance systems, security monitoring, and access control.

## Features 🚀
- **Real-time Face Recognition**: Detect and recognize faces instantly using a webcam.
- **Face Encoding and Storage**: Convert facial features into encodings and save them in a database.
- **Database Integration**: Store and retrieve data using Firebase.
- **User Authentication**: Verify individuals based on their facial data.
- **Optimized Performance**: Efficient use of OpenCV and machine learning algorithms for accurate recognition.

## Installation 🛠️

### Prerequisites
Ensure you have the following installed:
- Python 3.8+
- Required Python libraries (listed in `requirements.txt`)
- Firebase setup (for database integration)

### Steps to Set Up 🔧
1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd face-detection-main
   ```
2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Set up Firebase:**
   - Place your `serviceAccountKey.json` inside the project folder.
   - Ensure your Firebase project has Firestore and Storage enabled.
4. **Generate face encodings:**
   ```bash
   python FaceRecoginitionRealTimeDatabase/EncodeGenerator.py
   ```
5. **Run the face detection system:**
   ```bash
   python FaceRecoginitionRealTimeDatabase/main.py
   ```

## Usage 📸
- Execute `main.py` to start the face detection system.
- Use `AddDataToDatabase.py` to register new faces.
- Check Firebase to view stored facial data.
- Modify `EncodeGenerator.py` if you need to update encoding logic.

## Directory Structure 📂
```
face-detection-main/
│── FaceRecoginitionRealTimeDatabase/
│   ├── AddDataToDatabase.py
│   ├── EncodeGenerator.py
│   ├── main.py
│   ├── serviceAccountKey.json
│   ├── Images/
│   └── Resources/
│── README.md
│── requirements.txt
```

## Contributing 🤝
Feel free to submit issues or pull requests to improve the project.


