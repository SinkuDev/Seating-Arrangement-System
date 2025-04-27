# 🪑 Seating Arrangement System

A **web-based seating arrangement system** designed to automate and organize seating plans effectively.  
This project is built with **React Vite** (Frontend) and **Spring Boot Java** (Backend).

---

## 🚀 Project Features

- 📋 **Student and Room Management**  
- 🗺️ **Customizable Seating Blueprints**
- 🔄 **Automatic Student Allocation**
- 🛡️ **Authentication and Admin Panel**
- 📊 **Seating Reports and Downloads**

---

## 🛠️ Technologies Used

| Layer         | Technology         |
| ------------- | ------------------ |
| Frontend      | React + Vite        |
| Backend       | Spring Boot (Java)  |
| Database      | [Mention DB Here, e.g., MySQL] |
| Others        | [e.g., Maven, Axios] |

---

## 🖥️ Local Setup - How to Run this Project

Follow these simple steps to get the project running on your local machine:

### 📂 1. Clone the repository

```bash
git clone https://github.com/SinkuDev/Seating-Arrangement-System.git
cd your-repository
```

---

### 🌐 2. Setting up Frontend (React Vite)

```bash
cd frontend
npm install   # Install dependencies
npm run dev   # Start frontend server (default on http://localhost:5173)
```

✅ **Frontend ready at**: [http://localhost:5173](http://localhost:5173)

---

### 🔥 3. Setting up Backend (Spring Boot Java)

```bash
cd ../backend
```

- Edit `src/main/resources/application.properties` to configure your **database** credentials:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/your-db
spring.datasource.username=your-username
spring.datasource.password=your-password
```

- Then run:

```bash
./mvnw spring-boot:run
```

✅ **Backend ready at**: [http://localhost:8080](http://localhost:8080)

---

## ⚙️ Environment Requirements

| Tool               | Version |
| ------------------ | ------- |
| Node.js            | vXX.X.X |
| npm                | vXX.X.X |
| JDK                | 17+     |
| MySQL (or your DB) | v8+     |

---

## 🛣️ Project Structure

```plaintext
/seating-arrangement-system
|-- frontend/         # React Vite Webapp
|-- backend/          # Spring Boot Application
|-- README.md         # Project documentation
```

---

## 🧩 API Endpoints Overview

| Method | Endpoint         | Description                  |
| ------ | ---------------- | ---------------------------- |
| GET    | /api/seats        | Get available seats          |
| POST   | /api/allocate     | Allocate students to seats   |
| POST   | /api/login        | Admin Login                  |
| ...    | ...               | (Add more endpoints)         |

---

## 🙌 How to Contribute

1. Fork this repo 🍴
2. Create a branch (`git checkout -b feature/your-feature-name`) 🌿
3. Make your changes ✍️
4. Commit (`git commit -m 'Add feature'`) ✅
5. Push (`git push origin feature/your-feature-name`) 🚀
6. Open a Pull Request 🛠️

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 📬 Contact

- 👨‍💻 Developer: [Sinku singh]
- 📧 Email: [sinkusingh173@gmail.com]
- 🔗 GitHub: [https://github.com/SinkuDev]

---

# 🎯 Quick Start Commands

```bash
# Clone the project
git clone https://github.com/SinkuDev/Seating-Arrangement-System.git

# Install frontend
cd frontend
npm install
npm run dev

# Setup backend
cd ../backend
./mvnw spring-boot:run
```

---
