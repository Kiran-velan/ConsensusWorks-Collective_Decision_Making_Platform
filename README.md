# 🧠 Artificial Swarm Intelligence Platform for Decision Making & Opinion Gathering

Welcome to **ASI**, a collective intelligence platform that transforms group decision-making through dynamic visualizations, real-time interactions, and swarm-based logic.

---

## 🚀 What is Artificial Swarm Intelligence?

ASI is an interactive web platform that allows groups to participate in real-time decision-making sessions through sliders, visual feedback, and coordinated algorithms.

Inspired by **hive-mind** behavior and **swarm intelligence**, this tool aims to make democratic decisions **faster**, **more visual**, and **more inclusive**.

### 👥 Use Cases

- **Brainstorming sessions**
- **Public polls & surveys**
- **Team decision making**
- **Academic or research discussions**
- **Community consensus-building**

---

## 🎯 Vision

> "Empowering collective intelligence by enabling transparent, engaging, and visual decision-making experiences."

---

## 📸 Screenshots

| Home Page | Organizer Panel | Discussion Live |
|----------|-----------------|-----------------|
| <img width="1880" height="903" alt="Screenshot 2025-07-14 170325" src="https://github.com/user-attachments/assets/a4ca310a-969c-4f6c-9088-d94040b52737" />| <img width="1894" height="895" alt="Screenshot 2025-07-14 170530" src="https://github.com/user-attachments/assets/aa7bb6df-2bfa-4567-a794-901f5616c719" />| <img width="1905" height="918" alt="Screenshot 2025-07-14 170434" src="https://github.com/user-attachments/assets/69bddd22-ade1-4f69-a1ce-6f883682f216" /> |

> Visit [`screenshots`](https://drive.google.com/drive/folders/1_w8Odba2x5esbt5-LQl6QC38EALNndaX?usp=sharing) for more UI views.

---

## 🎥 Demo Video

▶️ [Watch the Platform in Action]()

---

## 🛠️ Built With

### ⚙️ Backend

- **Java 23**, **Spring Boot 3**
- **Spring MVC**, **Spring Security**
- **WebSocket** (STOMP) for real-time chat & slider input
- **Hibernate/JPA** with **MySQL** for persistence

### 🧠 Intelligence Engine

- **Custom Particle Swarm Optimization (PSO)** algorithm
- Calculates puck position from collective slider input
- Dynamic fitness evaluation & convergence mechanism

### 🎨 Frontend

- **Thymeleaf**
- **HTML5, CSS3, JavaScript**
- **Bootstrap 5** (for responsive UI)
- `html2pdf.js` for PDF report generation

---

## 🔍 Features Overview

### ✅ Organizer Panel
- Register/Login securely
- Create discussions with questions & multiple options
- Customize number of options that persist between rounds

### 🗳️ Discussion Sessions
- Time-based question & option rotation
- 6 sliders per user for opinion expression
- Real-time **puck movement** inside hexagon using PSO
- In-session **chat room** per discussion

### 📊 Results & Reports
- Finalized answers stored per question
- Public result view (`result.html`)
- Detailed analytics + fitness rankings in admin report (`report.html`)
- PDF download for reports

---

## 📐 Architecture
```
User ↔ Frontend (Thymeleaf + JS)
↕ WebSocket
Backend (Spring Boot) ↔ MySQL
↕ Microservice
PSO Engine (Python-based)
```

---

## 📂 Repository Structure (Codebase - Private Repo)

```
📁 config
📁 controller
📁 service
📁 repository
📁 entity
📁 dto
📁 security
📁 templates (Thymeleaf views)
📄 application.properties
```


---

## 🌍 Roadmap (Startup Vision)

- [x] Public discussion mode
- [x] PSO integration with dynamic rounds
- [x] Visual puck movement
- [x] Result reporting
- [ ] Real-time participant analytics
- [ ] Scalable cloud deployment
- [ ] Mobile-first redesign

---

## 💡 Why Artificial Swarm Intelligence?

🌀 Most platforms rely on basic polls.  
Swarm based Intelligence lets users **co-decide in real time** — not just cast static votes.

🧭 It visually **guides a group toward convergence**, helping uncover the **strongest collective opinion** — even in complex, multi-option scenarios.

---

## 🤝 Want to Collaborate?

- Collective intelligence
- Swarm-based decision systems
- Real-time WebSocket-driven architectures

Contact: **kiranvelan444@gmail.com**

---

## 📄 License

This public repository is for presentation purposes.  
The full codebase is private and not open-sourced currently.

---

## ⭐ Stay Tuned

More updates coming soon!  
Watch this repo for new demos, case studies, and collaboration announcements.

