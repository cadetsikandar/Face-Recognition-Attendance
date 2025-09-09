# 🎓 Face Recognition Attendance System

A deep learning–based **real-time face recognition attendance system** using:
- **MTCNN** for face detection
- **InceptionResnetV1** (FaceNet) for embeddings
- **OpenCV** for live webcam feed
- **Pandas + Excel** for attendance tracking

---

## 🚀 Features
- Enroll new students from images in `dataset/StudentName/`
- Save and load face embeddings (`faces_db.npz`)
- Real-time face recognition from webcam
- Automatic attendance logging into `attendance.xlsx`
- Marks each student only once per day

---

## 📂 Repository Structure
```bash
Face-Recognition-Attendance/
├── data/ # student face images
├── Notebook/ # source code
├── requirements.txt # dependencies
├──  assets # store demo
└── README.md # project docs
````


## 🎥 Demo

https://github.com/cadetsikandar/Face-Recognition-Attendance/blob/main/assets/demo.mp4



---

## 🔧 Installation
```bash
git clone https://github.com/cadetsikandar/Face-Recognition-Attendance.git
cd Face-Recognition-Attendance
pip install -r requirements.txt
````

📊 Output Example

Attendance file (attendance.xlsx):

Name	2025-09-02
Absar	P
Mujahid	A
Sikandar	P
👨‍💻 Author

Sikandar Ali
AI & Computer Vision Enthusiast 🚀

📜 License

MIT License


---

⚡ Next Steps:
1. I can split your big script into **modular files (`database.py`, `enrollment.py`, etc.)** so your repo looks very professional.  
2. Then you just need to run:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Face Recognition Attendance System"
   git branch -M main
   git remote add origin https://github.com/cadetsikandar/Face-Recognition-Attendance.git
   git push -u origin main
   ````
