# 📚 Quiz Application in Java

An interactive Java-based quiz platform designed for **teachers** and **students** to create, manage, and take quizzes on various topics.  
Built using **Java Swing (JFrame)** for the interface and **SQL** for secure data management.  

![Quiz App Screenshot](screenshots/main_menu.png)

---

## 📌 Table of Contents
- [Introduction](#introduction)
- [Background](#background)
- [Motivation](#motivation)
- [Objectives](#objectives)
- [Proposed Method](#proposed-method)
- [Methodology](#methodology)
- [Technologies Used](#technologies-used)
- [Results](#results)
- [Conclusion](#conclusion)
- [Acknowledgement](#acknowledgement)
- [Contributors](#contributors)
- [Installation & Setup](#installation--setup)
- [Screenshots](#screenshots)
- [License](#license)

---

## 📝 Introduction
The purpose of this project is to create an **accessible and enjoyable Java Quiz Application** to enhance learning experiences for educators, students, and quiz enthusiasts.  
The application offers:
- **User-friendly navigation**
- **Inclusive design** for all abilities
- Multimedia support (**images, audio, video**)
- Real-time participation and score comparison
- Secure database management for scalability

---

## 📖 Background
This project responds to the **changing educational landscape** due to the **COVID-19 pandemic**.  
With physical classrooms limited, there is a growing demand for **virtual, interactive learning tools**.  
The Java Quiz Application addresses this gap, providing a platform for **knowledge assessment and reinforcement**.

---

## 💡 Motivation
The motivation lies in **turning adversity into opportunity**.  
By harnessing technology, we provide an engaging way to continue learning and testing knowledge **virtually**, even when face-to-face classes are impossible.

---

## 🎯 Objectives
1. **Create a User Interface** – Easy access to quizzes, questions, and results.  
2. **Question Management** – Add, edit, and delete quiz questions.  
3. **Scoring System** – Real-time score calculation and display.  
4. **Multiple Choice Support** – Single correct answer selection.  
5. **User Authentication** – Secure login for both students and teachers.  
6. **Timed Quizzes** – Option to set time limits.  
7. **Feedback** – Show correct answers for incorrect responses.  
8. **Admin Panel** – Teacher dashboard to manage quiz content.

---

## 🔧 Proposed Method
Our approach:
- **Java Swing (JFrame)** for the interface
- **SQL** for storing questions, users, and results
- **NetBeans IDE** for development
- **JDBC Connector** for database integration
- **Authentication system** for secure access
- **Score tracking & analytics**
- **Thorough testing** using Java frameworks

---

## 🛠 Methodology
The application is built around multiple **Java classes**, each serving a specific purpose:

1. **Index Class** – Entry point of the application; directs teachers and students.  
2. **Login Teacher Class** – Authenticates teachers and grants admin access.  
3. **Admin Home Class** – Teacher dashboard for quiz customization.  
4. **Add New Question Class** – Adds new quiz questions to the database.  
5. **Update Question Class** – Allows editing of existing questions.  
6. **Delete Question Class** – Removes unwanted questions.  
7. **All Question Class** – Displays all questions in the database.  
8. **All Student Result Class** – Shows performance data for all students.  
9. **Student Details Class** – Collects personal info before quiz start.  
10. **Instructions Class** – Displays rules and guidelines.  
11. **Quiz Exam Student Class** – Main quiz interface with MCQs, timers, and real-time score updates.  
12. **Successfully Submitted Class** – Confirmation after quiz submission.  
13. **Acknowledgement Class** – Displays confirmation messages for actions.

---

## 💻 Technologies Used
- **Java** (Swing – JFrame)
- **SQL** (Database for storing quiz data)
- **NetBeans IDE**
- **JDBC SQL Connector**
- **Custom Java Authentication**
- **Graphics & UI Assets**

---

## 📊 Results
- Fully functional **quiz management system**
- Secure **database storage** for students and quiz content
- **Admin dashboard** for teachers
- **Timed and untimed quizzes**
- Instant **feedback system**

---

## ✅ Conclusion
This project successfully delivers a **secure, user-friendly, and interactive quiz platform**.  
It demonstrates how **technology can enhance education** in both traditional and remote learning environments.  
Looking ahead, this system can be extended to include:
- Online quiz hosting
- Mobile app integration
- More question types and difficulty levels

---

## 🙏 Acknowledgement
We thank **MD. Mahbub-Or-Rashid**, Assistant Professor, Department of CSE, BUBT, for his invaluable guidance and encouragement throughout the project.  
Special thanks to the **Almighty** for giving us strength and perseverance to complete this work.

---

## 👥 Contributors
- **MD. Ashikur Rahman** (21225103471) – Intake 49/06  
- **Abdullah Al Mahmud Joy** (21225103506) – Intake 49/06  
- **Kaspia Alam** (21225103487) – Intake 49/06  
- **Mirza Niaz Morshed** (21225103467) – Intake 49/06  
- **Ayesha Siddika Esha** (21225103495) – Intake 46/06  

---

## ⚙ Installation & Setup
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/username/quiz-application-java.git
cd quiz-application-java
