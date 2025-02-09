# Advanced Attendance System

![Attendance System](https://via.placeholder.com/800x400?text=Advanced+Attendance+System)

An **Advanced Attendance System** built using **Python** and **Django**, featuring facial recognition for automated attendance tracking. This system enhances efficiency by eliminating manual attendance marking.

## 🚀 Features

- 🎭 **Facial Recognition** using OpenCV and DeepFace
- 🌐 **Django Backend** for handling requests and storing data
- 📊 **MySQL Database** for secure data storage
- 📸 **Real-time Webcam Capture** for attendance verification
- 📅 **Date & Time Logging**
- 📜 **User Authentication & Role Management**
- 📈 **Attendance Reports Generation**
- 📤 **Export Data to CSV/Excel**

## 🛠️ Tech Stack

- **Backend:** Django, Django REST Framework, FastAPI (optional for APIs)
- **Frontend:** HTML, CSS, JavaScript (or React for advanced UI)
- **Database:** MySQL
- **AI/ML:**
- asgiref==3.2.10
- click==7.1.2
- cmake==3.17.3
- Django==3.0.14
- django-filter==2.3.0
- dlib==19.8.1
- face-recognition==1.3.0
- face-recognition-models==0.3.0
- numpy==1.19.0
- opencv-python==4.2.0.34
- Pillow==7.2.0
- pytz==2020.1
- sqlparse==0.3.1

## 📸 Screenshots

### 🔹 Admin
![Login](https://github.com/aditya-devm02/advanced-attendance-system-/blob/main/advanced%20attendace%20system/assets/WhatsApp%20Image%202024-12-28%20at%2010.51.48.jpeg)

### 🔹 Dashboard
![Dashboard](https://github.com/aditya-devm02/advanced-attendance-system-/blob/main/advanced%20attendace%20system/assets/WhatsApp%20Image%202024-12-28%20at%2010.51.48%20(1).jpeg )

![Dashboard]( https://github.com/aditya-devm02/advanced-attendance-system-/blob/main/advanced%20attendace%20system/assets/WhatsApp%20Image%202024-12-28%20at%2010.51.48%20(2).jpeg )

### 🔹 Facial Recognition in Action
![Face Recognition](https://github.com/aditya-devm02/advanced-attendance-system-/blob/main/advanced%20attendace%20system/assets/2729E475-F882-423B-9929-54B155E5DF27_4_5005_c.jpeg)

## 🚀 Installation

1️⃣ Clone the repository:
```sh
git clone https://github.com/yourusername/advanced-attendance-system.git
cd advanced-attendance-system
```

2️⃣ Create a virtual environment:
```sh
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3️⃣ Install dependencies:
```sh
pip install -r requirements.txt
```

4️⃣ Apply database migrations:
```sh
python manage.py makemigrations
python manage.py migrate
```

5️⃣ Create a superuser:
```sh
python manage.py createsuperuser
```

6️⃣ Run the development server:
```sh
python manage.py runserver
```

7️⃣ Open the system in a browser:
```
http://127.0.0.1:8000/
```

## 🔥 Usage

1. **Admin Login**: Access the admin dashboard to manage users.
2. **Register Employees/Students**: Add users with facial images for recognition.
3. **Start Attendance**: The system detects faces and marks attendance.
4. **Generate Reports**: Export attendance records.

## 🛡 Security Considerations

- ✅ Secure authentication with Django
- ✅ Encrypted password storage
- ✅ Role-based access control (Admin, Teacher, Student)

## 🤝 Contribution

1. Fork the project
2. Create a new branch (`feature-xyz`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature-xyz`)
5. Open a Pull Request

## 📜 License
This project is **open-source** under the **MIT License**.

---

Made with ❤️ using **Django** and **OpenCV**!
