# Student Web Application

A simple web application developed using Python Flask.

## Technologies
- Python
- Flask
- Docker
- Git
- GitHub

## Run locally

pip install -r requirements.txt

python app.py

Open:
http://localhost:5000

## Build Docker Image

docker build -t student-web-app:v1 .

## Run Docker Container

docker run -d -p 5000:5000 --name student-container student-web-app:v1