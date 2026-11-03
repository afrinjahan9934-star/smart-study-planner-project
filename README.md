# 📚 Smart Study Planner

A simple and user-friendly web application that helps students organize their study tasks by adding subjects, study dates, and task descriptions.

## 🌐 Live Demo

👉 **[Open Smart Study Planner](https://smart-study-planner-eqd3.onrender.com)**

You can open the application on a laptop, mobile phone, tablet, or any other device with a web browser.

---

## ✨ Features

- ➕ Add new study tasks
- 📖 Add the subject for each task
- 📅 Select a study date
- ✅ Mark completed tasks
- 🗑️ Remove tasks
- 📋 View all study tasks in one place
- 📱 Responsive interface that works on different devices
- 🌐 Deployed online using Render
- 🔗 Source code hosted on GitHub

---

## 🛠️ Technologies Used

### Backend
- Java
- Spring Boot
- Maven

### Frontend
- HTML
- CSS
- JavaScript

### Deployment & Version Control
- Git
- GitHub
- Render

---

## 📂 Project Structure

```text
smart-study-planner-spring-boot/
│
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── example/
│   │   │           └── studyplanner/
│   │   │               └── SmartStudyPlannerApplication.java
│   │   │
│   │   └── resources/
│   │       ├── static/
│   │       │   └── index.html
│   │       └── application.properties
│   │
│   └── test/
│
├── .gitignore
├── pom.xml
├── mvnw
├── mvnw.cmd
└── README.md
```

---

## 🚀 Run the Project Locally

### 1. Clone the repository

```bash
git clone [https://github.com/afrinjahan9934-star/smart-study-planner.git]
```

### 2. Open the project

```bash
cd smart-study-planner
```

### 3. Run the Spring Boot application

On Windows:

```bash
mvnw.cmd spring-boot:run
```

Or, if Maven is installed:

```bash
mvn spring-boot:run
```

### 4. Open the application

Open your browser and visit:

```text
http://localhost:8080
```

---

## 📱 How to Use

1. Open the Smart Study Planner.
2. Enter a study task.
3. Enter the subject.
4. Select the study date.
5. Click **Add task**.
6. Your task will appear under **My study tasks**.
7. Mark a task as completed when you finish studying.
8. Remove tasks when they are no longer needed.

---

## 🌐 Deployment

The application is deployed using **Render**.

Every time changes are pushed to the GitHub repository, the deployment can be updated automatically through Render.

### Live Application

**https://smart-study-planner-eqd3.onrender.com**

---

## ⚠️ Data Storage

The current version is designed as a simple study-planning application. Task data is stored locally in the user's browser.

This means:

- Tasks saved on one device may not appear on another device.
- Clearing browser data can remove locally stored tasks.
- Different devices/browsers have separate task data.

A future version could use a database such as PostgreSQL so that tasks can be synchronized across devices.

---

## 🔮 Future Improvements

Some possible improvements for future versions:

- 👤 User accounts and login
- ☁️ Cloud database
- 🔄 Synchronization across devices
- 🔔 Study reminders
- 📊 Study progress dashboard
- 🎯 Daily and weekly study goals
- 🔍 Search and filter tasks
- ✏️ Edit existing tasks
- 🌙 Dark mode
- 📱 Progressive Web App (PWA) support

---

## 🎯 Project Goal

The goal of this project is to create a simple digital planner that helps students organize their study activities and keep track of their progress.

It also serves as a practical project for learning and applying:

- Java
- Spring Boot
- Maven
- HTML
- CSS
- JavaScript
- Git
- GitHub
- Cloud deployment

---

## 👨‍💻 Author

**Afrin Jahan**

GitHub:  
https://github.com/afrinjahan9934
---

## 📄 License

This project is open source and available for learning and educational purposes.
