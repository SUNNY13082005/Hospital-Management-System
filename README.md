
# 🏥 Hospital Management System

A web-based Hospital Management System built using **PHP**, **MySQL**, **HTML5**, **CSS3**, **Bootstrap**, and **JavaScript**. The system manages hospital operations efficiently, offering modules for patients, doctors, and administrators.

---

## 📌 Features Implemented

✅ **Patient Module**
- Patient registration/login  
- Appointment booking  
- Appointment history view  
- Appointment cancellation  

✅ **Doctor Module**
- Doctor login  
- View/manage appointments  
- Search appointments by patient contact  

✅ **Admin Module**
- View all patients, doctors, appointments  
- Add and remove doctors  
- View feedback/queries  
- Remove doctors  

✅ **Other**
- Appointment cancellation with status tracking  
- Basic search functionality  
- Bill payment receipts  

---

## 💡 What Can Be Improved / Added

🚀 Accept appointment requests by doctors (to acknowledge/approve)  
🚀 Prevent duplicate user registration with same email  
🚀 Encrypt and securely store passwords (e.g., using bcrypt or PHP’s `password_hash`)  
🚀 Hide password fields from admin view  
🚀 Implement pagination across list views  
🚀 Fix duplicate records in bill receipts for repeat doctor visits  
🚀 Add more fields in prescription and payment statements (e.g., payment date, amount)  
🚀 Enable data export (Excel/CSV) in admin panel  

---

## ⚙️ Technologies Used

- **PHP** (Backend logic)  
- **MySQL** (Database)  
- **HTML5 / CSS3 / Bootstrap** (Frontend)  
- **JavaScript** (Dynamic content)  
- **TCPDF** (PDF generation)  
- **XAMPP** (Local web server environment)

---

## 🛠️ Installation & Setup

1️⃣ **Install prerequisites**
- [XAMPP](https://www.apachefriends.org/index.html)  
- Code editor (e.g., VS Code, Sublime Text)  
- Modern web browser  

2️⃣ **Clone / extract project**
```bash
Move the extracted folder to XAMPP's `htdocs` directory
```

3️⃣ **Start server**
- Open XAMPP Control Panel  
- Start **Apache** and **MySQL**  

4️⃣ **Database setup**
- Visit `localhost/phpmyadmin`  
- Create database: `myhmsdb`  
- Import `myhmsdb.sql`  

5️⃣ **Run project**
- Open browser → `localhost/Hospital-Management-System-master`  

---

## ❗ Challenges Faced

⚠️ Handling appointment conflicts for the same doctor  
⚠️ Ensuring proper user-session handling  
⚠️ PDF generation with dynamic data  
⚠️ Managing data integrity with multiple user roles  

---

## ✨ Future Enhancements

- Role-based access control  
- Notification/email alerts  
- Analytics dashboard for admin  
- REST API for mobile integration  

---

## 📂 Project Structure

```
Hospital-Management-System-master/
│
├── TCPDF/           # PDF library
├── assets/          # CSS, JS, images (if present)
├── config/          # Configuration files
├── *.php            # Main PHP files
└── myhmsdb.sql      # Database schema
```

---

## ✉️ Contact

_For feedback / contributions: Niranjan Babu Kotapati - [126015048@sastra.ac.in]_
