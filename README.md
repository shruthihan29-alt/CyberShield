# 🛡️ CyberShield — Password Security Analyzer

> A professional full-stack cybersecurity web application 
> that analyzes password strength, entropy, crack time 
> and vulnerabilities in real time.

🌍 **Live Demo:** https://shruthihan29-alt.github.io/CyberShield/

---

## 🖥️ Preview

![CyberShield Preview](https://shruthihan29-alt.github.io/CyberShield/)

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🔐 **Strength Score** | Real-time 0–100 security score with A+ to F grades |
| 📊 **Entropy Calculation** | Shannon formula: H = L × log₂(R) |
| ⏱️ **Crack Time** | Online · Offline · GPU · Dictionary attack simulation |
| 🕵️ **Dictionary Detection** | Checks against 10M+ common passwords |
| 📈 **Radar Chart** | Interactive 5-dimension security visualization |
| 📄 **PDF Reports** | Professional downloadable security reports |
| 🛡️ **Security Hardened** | BCrypt · Rate Limiting · CORS · CSP Headers |

---

## 🛠️ Tech Stack

### Frontend
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap_5-563D7C?style=flat&logo=bootstrap&logoColor=white)

### Backend
![Java](https://img.shields.io/badge/Java_17-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot_3.2-6DB33F?style=flat&logo=spring-boot&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL_9-4479A1?style=flat&logo=mysql&logoColor=white)

### Tools
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat&logo=chartdotjs&logoColor=white)

---

## 🔒 Security Features Implemented

---

## 📊 How It Works

User enters password

↓
13-point security scan runs instantly

↓
Shannon entropy calculated: H = L × log₂(R)

↓
Crack time estimated across 4 attack vectors

↓
Radar chart + recommendations generated

↓
PDF report available for download

---

## 📡 REST API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/api/analyze` | Full password analysis |
| GET | `/api/history` | Last 10 analyses |
| GET | `/api/stats` | Dashboard statistics |
| GET | `/api/health` | Health check |
| GET | `/api/report/{id}` | Analysis by ID |

---

## 🚀 Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/shruthihan29-alt/CyberShield.git
cd CyberShield

# 2. Setup database
mysql -u root -p < database/schema.sql
mysql -u root -p < database/seed.sql

# 3. Configure backend
# Edit backend/src/main/resources/application.properties
# Set your MySQL password

# 4. Run backend
cd backend
mvn spring-boot:run

# 5. Open frontend
# Open index.html with Live Server in VS Code
```

---

