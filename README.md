# Face Recognition Attendance System 🎓📷

A smart attendance management system using **Python**, **OpenCV**, and **Tkinter GUI**. This project uses real-time face recognition to mark student attendance and maintains a record in CSV format.

---

## 🚀 Features

- 🎥 Real-time face detection & recognition using webcam
- 🧠 Face training using OpenCV's LBPH algorithm
- 📂 Stores student data with name and ID
- 📊 Attendance is saved automatically in CSV format
- 🖥️ User-friendly interface with Tkinter

---

## 🛠️ Tech Stack

- **Python 3.x**
- **OpenCV**
- **Tkinter**
- **NumPy**
- **CSV module**

---

## 📂 Project Structure

```
Face-Recognition-Attendance/
├── main.py                  # Launch GUI
├── student.py               # Register new student
├── train.py                 # Train model on student data
├── attendance.py            # Face recognition and attendance marking
├── images/                  # Folder to store student face images
├── StudentDetails.csv       # Stores student details
├── Attendance/              # Stores daily attendance files
├── Trainner/                # Contains trained model (see below)
└── README.md
```

---

## ⚠️ Important Note: Missing `Trainner.yml`

Due to GitHub’s file size restrictions, the trained model file `Trainner.yml` is **not included** in the repository.  

👉 You can download it manually from the link below and place it inside the `Trainner` folder.

📎 [Download Trainner.yml from Google Drive](https://drive.google.com/file/d/1GC3Ul136YYUFqOMHRnz8kuX9EsPI7TxS/view?usp=sharing)

> After downloading, place it inside the folder:
> ```
> Face-Recognition-Attendance/Trainner/Trainner.yml
> ```

---

## 🧪 How to Run

```bash
pip install opencv-python numpy
python main.py
```

---

## 📝 Output

- Student face images saved in: `images/`
- Trained model saved in: `Trainner/Trainner.yml`
- Attendance logs saved in: `Attendance/Attendance_<date>.csv`

---

## 🤝 Contribution

Feel free to fork, modify, or raise issues. Contributions are welcome!

---

## 📌 Author

**Amit Singh**  
📫 Email: asr7420@gmail.com  
🌐 GitHub: [asr7420](https://github.com/asr7420)

---

## 🏷️ Tags

`#FaceRecognition` `#OpenCV` `#AttendanceSystem` `#PythonProject` `#TkinterGUI` `#AI` `#StudentProject`
