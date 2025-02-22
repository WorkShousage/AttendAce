### **AttendACe – Face Recognition-Based Attendance System**  

AttendACe is a smart and efficient attendance system designed for **schools, colleges, and workplaces**. It automates attendance marking using **face recognition** and provides a **QR code backup** if recognition fails. Optimized for **Raspberry Pi deployment**, it can also be fully tested and developed on a laptop.  

---

### **Key Features**  
- **Face Recognition** – Uses OpenCV and dlib for real-time detection.  
- **QR Code Backup** – Prevents misuse with dynamically generated, non-screenshotable QR codes.  
- **Secure Data Storage** – Supports **CSV, SQLite, or Firebase** for flexibility.  
- **Optimized for Raspberry Pi** – Can run on low-cost hardware while being fully testable on a laptop.  
- **Cloud Sync** – Option to store attendance in Firebase for real-time updates.  
- **Multi-User Collaboration** – Supports Git-based teamwork with virtual environments.  

---

### **Tech Stack**  
- **Programming Language:** Python  
- **Libraries:** OpenCV, dlib, face-recognition, Flask, qrcode[pil], pyzbar  
- **Database:** CSV for local storage, SQLite for lightweight database needs, Firebase for cloud storage  
- **Deployment:** Raspberry Pi with a camera module for face recognition and a display module for QR scanning  

---

### **How It Works**  
1. **Face Recognition** – The system captures and processes images, comparing them with stored data to mark attendance.  
2. **QR Code Backup** – If face recognition fails, the user scans a **temporary QR code** from their mobile app.  
3. **Attendance Logging** – Data is securely stored and can be accessed in real-time.  
4. **Raspberry Pi Deployment** – Can be installed on a Raspberry Pi with necessary optimizations.  

---

### **Development & Collaboration**  
- **Version Control:** Git is used for managing code and collaboration.  
- **Virtual Environment:** A Python virtual environment is used to avoid dependency conflicts.  
- **Requirements Management:** Dependencies are listed in `requirements.txt` for easy setup.  

AttendACe provides a **fast, secure, and fraud-resistant** solution for attendance tracking, eliminating the need for manual registers or RFID systems. 
