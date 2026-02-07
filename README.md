# 🚀 Portfolio Web Server (FastAPI + Docker + Nginx)

FastAPI 기반의 웹 애플리케이션을 Docker로 컨테이너화하고  
Nginx Reverse Proxy를 통해 EC2에 배포한 포트폴리오 프로젝트입니다.

---

## 🧱 Architecture

![architecture](docs/architecture.drawio.png)

- AWS EC2
- Docker & Docker Compose
- Nginx (Reverse Proxy)
- FastAPI (Uvicorn)
- Jinja2 Template

---

## 📁 Project Structure

portfolio-app
├─ app
│ ├─ main.py
│ ├─ static
│ └─ templates
├─ nginx
│ └─ default.conf
├─ Dockerfile
├─ docker-compose.yml
├─ requirements.txt
└─ README.md

---

## ⚙️ Tech Stack

- **Backend**: FastAPI
- **Web Server**: Nginx
- **Container**: Docker, Docker Compose
- **Cloud**: AWS EC2 (Linux)
- **CI/CD (optional)**: GitHub Actions

---

## 🚀 How to Run

```bash
git clone https://github.com/your-id/portfolio-app.git
cd portfolio-app
docker-compose up -d --build
