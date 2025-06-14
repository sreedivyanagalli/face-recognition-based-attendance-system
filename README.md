-Face Recognition-Based Attendance System-

-Project Objective-
This project implements a real-time face recognition system to automate attendance marking in classrooms or organizations. Using computer vision and face encoding, it detects and identifies individuals via webcam and logs their presence with timestamps.

-Tech Stack-
- Python
- OpenCV – Real-time video capture and face detection
- face_recognition (dlib) – Face encoding and matching
- NumPy / Pandas – Data processing
- CSV Logging – Attendance storage

-Features-
- Real-time webcam-based face recognition
- Encodes known faces and matches with live video feed
- Automatically logs recognized names with date & time
- Simple CSV file acts as the attendance ledger

-Folder Structure-
```
/face-recognition-based-attendance-system
│
├── main.py              # Main script for detection & logging
├── images/              # Folder with known faces
├── attendance.csv       # Logged attendance entries
```

-How to Run-
1. Clone the repository:
   ```bash
   git clone https://github.com/sreedivyanagalli/face-recognition-based-attendance-system.git
   cd face-recognition-based-attendance-system
   ```
2. Install dependencies:
   ```bash
   pip install opencv-python face_recognition numpy pandas
   ```
3. Add face images to the `images/` folder (use clear frontal photos).
4. Run the application:
   ```bash
   python main.py
   ```
5. Attendance gets saved in `attendance.csv`.

-Future Enhancements-
- GUI dashboard with Tkinter or Flask
- Database-backed logging (SQLite, PostgreSQL)
- Email/SMS notifications for entry
- Mask detection or liveness verification
  
-Skills-
`Face Recognition`, `OpenCV`, `Computer Vision`, `Python`, `Image Processing`, `Automation`, `AI Attendance System`, `CSV Logging`, `Real-Time Detection`
