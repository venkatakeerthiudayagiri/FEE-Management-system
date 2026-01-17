# Fee Management System (FMS)

## 📌 Overview
The **Fee Management System (FMS)** is a web-based application developed to digitalize and simplify student fee management in educational institutions.

This project was developed in **2023** as a **college mini project**, inspired by real challenges faced by students and college management regarding fee transparency, accessibility, and manual record handling.

The system provides a **dedicated platform for fee-related queries**, allowing students to securely access their fee details while enabling administrators to efficiently manage and track fee records.

---

## 💡 Motivation & Real-World Background
During our academic period, students frequently faced issues such as:
- Difficulty in accessing fee payment details
- Lack of transparency in paid and due amounts
- Dependency on manual records maintained by administration

To address these problems, we designed and implemented the **Fee Management System**, which:
- Provides students direct access to their fee information
- Reduces administrative workload
- Minimizes manual errors and duplicate entries

The concept was appreciated by the college management, and discussions were held to scale the system further and deploy it as a dedicated fee management portal.

---

## 🎯 Objectives
- Digitize fee management processes
- Reduce manual work and human errors
- Provide role-based secure access
- Enable real-time fee status tracking
- Improve transparency between students and administration

---

## 👥 User Roles

### 🔹 Admin
- Secure login
- Add and manage students
- Create and manage branches
- Define fee structures
- Record and update fee payments
- Generate fee reports
- Change password and logout

### 🔹 Student (User)
- Register and login
- View fee details (paid / due)
- Access fee reports
- Change password and logout

---

## 🛠️ Technologies Used
- **Frontend:** HTML5, CSS3  
- **Backend:** PHP  
- **Database:** MySQL  
- **Server:** Apache (Localhost)  
- **Architecture:** Client–Server Model  

---

## 📐 System Design & Documentation
The project includes detailed UML and design documentation such as:
- Use Case Diagram
- Activity Diagram
- Sequence Diagram
- Class Diagram
- Component Diagram
- Deployment Diagram
- State Diagrams

These diagrams are included in the `diagrams/` folder.

---

## 📂 Project Structure

```text
fee-management-system/
│
├── README.md
├── index.html
├── teacher.html
├── hi.html
├── style.css
├── user.png
│
├── diagrams/
│   ├── use-case-diagram.png
│   ├── class-diagram.png
│   ├── sequence-view-fee-report.png
│   ├── component-diagram.png
│   └── deployment-diagram.png
│
├── Screenshots/
│   └── fee-report.png
│
└── extras/
    └── (practice and experimental files)
---

## ▶️ Steps to Execute the Project

1. Install a local web server such as **XAMPP** or **WAMP**.
2. Clone this repository or download it as a ZIP file.
3. Copy the project folder into the server root directory:
   - `htdocs` (for XAMPP)
   - `www` (for WAMP)
4. Start **Apache** and **MySQL** from the control panel.
5. Create a MySQL database (e.g., `fee_management_system`).
6. Create the required tables in MySQL as per the database design described in the project documentation.
7. Configure database credentials in the PHP files.
8. Open a web browser and navigate to::   http://localhost/fee-management-system/
9. Login as Admin or Student to access the system features.

> **Note:**  
> Database schema and table structures were created manually during development and are documented in the project report.

---

## 📸 Sample Output
The system displays:
- Academic year-wise fee details
- Fee categories (Tuition, Transport, Library, etc.)
- Paid amount and due amount
- Receipt numbers and payment dates

Sample screenshots are available in the `Screenshots/` folder.

---

## 🚀 Future Enhancements
- Online payment gateway integration
- Email/SMS notifications for fee updates
- Advanced reporting and analytics dashboard
- Mobile-friendly responsive UI
- Multi-institution support

---

## 🏫 Academic Context
- **Developed as:** Mini Project (Project-I)
- **Year:** 2023
- **Institution:** R.V.R & J.C. College of Engineering (Autonomous)
- **Department:** Information Technology

---

## 🤝 Acknowledgment
This project was developed as part of the academic curriculum with guidance from faculty members and support from college management.

---

## 📄 License
This project is intended for **academic and learning purposes**.  
Any large-scale deployment may require further validation and institutional approval.

