# Docker Nginx Hello Server 🐳

This is a simple DevOps practice project to learn Docker and containerized web servers.

## What it does

Runs an Nginx server inside Docker and serves a custom HTML page.

## Project structure

docker-nginx-hello/
├── Dockerfile
├── .gitignore
├── README.md
└── app/
    └── index.html

## How to run

Build image:

docker build -t docker-nginx-hello .

Run container:

docker run -p 8080:80 docker-nginx-hello

Open in browser:

http://localhost:8080
