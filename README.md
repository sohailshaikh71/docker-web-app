# Docker Web App 🚀

## 📌 Description
This project demonstrates how to containerize a simple Python Flask application using Docker.

## ⚙️ Tech Stack
- Python
- Flask
- Docker

## 📂 Project Structure
.
├── app.py  
├── requirements.txt  
├── Dockerfile  
└── README.md  

## 🐳 Docker Setup

### Build Image
docker build -t docker-web-app .

### Run Container
docker run -p 5000:5000 docker-web-app

## 🌐 Access Application
Open browser:
http://localhost:5000

## 🎯 Key Learning
- Dockerfile creation  
- Containerization  
- Running app inside container  
