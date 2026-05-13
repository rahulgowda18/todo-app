# Flask Visitor Counter App

A simple Flask application that counts the number of visitors.

## Features

- Simple Flask web application
- Visitor counter
- Dockerized application
- Beginner-friendly DevOps project

---

## Project Structure

flask-app/
│
├── app.py
├── Dockerfile
├── requirements.txt
└── templates/
    └── index.html

---

## Requirements

- Python 3
- Docker Desktop

---

## Run Locally

### Install Dependencies

```bash
pip install -r requirements.txt

**## start app**
python app.py

**##open browser**
http://localhost:5000

**##docker commands**
##docker build command
docker build -t flask-app .

## docker run command
docker run -p 5000:5000 --name flask-container flask-app

## docker stop command
docker stop flask-container

## docker remove container
docker rm flask-container

## Technology Used
Pyhon
Docker
Flask


