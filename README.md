# 🧠 ConsensusWorks 
# Platform for Decision Making & Opinion Gathering

Welcome to **ConsensusWorks**, a collective intelligence platform that transforms group decision-making through dynamic visualizations, real-time interactions, and game theory-based logic.

---

## 🚀 What is Game Engine here? - Bradley Terry Model

This is an interactive web platform that allows groups to participate in real-time decision-making sessions through sliders, visual feedback, and coordinated algorithms.

Inspired by **hive-mind** behavior and **Game Theory**, this tool aims to make democratic decisions **faster**, **more visual**, and **more inclusive**.

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
| <img width="1880" height="903" alt="Screenshot 2025-10-17 151533" src="https://github.com/user-attachments/assets/6f1177c0-8429-4034-8b2d-38bc7b636b35" />| <img width="1894" height="895" alt="Screenshot 2025-10-17 151520" src="https://github.com/user-attachments/assets/2940ff7e-ccd9-4608-9dd4-4b3b4524b5cc" />| <img width="1905" height="918" alt="Screenshot 2025-10-10 001254" src="https://github.com/user-attachments/assets/b298a84f-abab-4489-bb9e-0a48eb04fbdf" /> |

> Visit [`screenshots`](https://drive.google.com/drive/folders/1_w8Odba2x5esbt5-LQl6QC38EALNndaX?usp=sharing) for more UI views.

---

## 🎥 Demo Video

▶️ [Watch the Platform in Action](https://drive.google.com/file/d/199BYkdkJxsuq-tObgBuV-AeU-iD2P6EA/view?usp=sharing)

---

## 🛠️ Built With

### ⚙️ Backend

- **Java 21**, **Spring Boot 3**
- **Spring MVC**, **Spring Security**
- **WebSocket** (STOMP) for real-time chat & slider input
- **Hibernate/JPA** with **MySQL** for persistence
- **Redis** Caching
- **Microservice Architecture** for Game Engine 

### 🧠 Intelligence Engine

- **Bradley Terry Model**
- Calculates strength of each options from collective slider input
- Dynamic fitness evaluation & convergence mechanism
- Participants negotiate and re-evaluate their preferences to attain consensus

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
- Real-time **visual** representation
- In-session **chat room** per discussion

### 📊 Results & Reports
- Finalized answers stored per question
- Detailed analytics + rankings in the report (`report.html`)
- PDF download for reports

---

## 📐 Architecture
```
User ↔ Frontend (Thymeleaf + JS)
↕ WebSocket
Backend (Spring Boot) ↔ MySQL
↕ Microservice
BTM Engine (Python-based)
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
- [x] BTM integration with dynamic rounds
- [x] Visual movement
- [x] Result reporting
- [ ] Real-time participant analytics

---

## 💡 Why This?

🌀 Most platforms rely on basic polls.  
Swarm based Intelligence lets users **co-decide in real time** — not just cast static votes, where everyone agrees with the result.

🧭 It visually **guides a group toward convergence**, helping uncover the **strongest collective opinion** — even in complex, multi-option scenarios.

---

## 🤝 Want to Collaborate?

- Collective intelligence
- Swarm-based decision systems
- Real-time WebSocket-driven architectures

Contact: **kiranvelan007@gmail.com**

---

## 📄 License

This public repository is for presentation purposes.  
The full codebase is private and not open-sourced currently.

---

## ⭐ Stay Tuned

More updates coming soon!  
Watch this repo for new demos, case studies, and collaboration announcements.

