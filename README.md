🐳 My First Docker Container Project

This is my first beginner-level Docker project, created to understand the basics of Docker, containers, and DevOps fundamentals.

In this project, I containerized a simple HTML webpage using Docker and successfully ran it inside a Docker container.

📌 Project Overview

A basic HTML webpage

Dockerfile to build a Docker image

Docker container runs the webpage using Nginx

Accessible on browser via localhost

This project helped me understand:

What Docker is

How containers work

How to create and run a Docker image

🛠️ Technologies Used

Docker

HTML

Nginx

Git & GitHub

📂 Project Structure
.
├── Dockerfile
├── index.html
└── README.md

🚀 How to Run This Project
1️⃣ Build the Docker image
docker build -t my-first-docker-app .

2️⃣ Run the Docker container
docker run -d -p 8080:80 my-first-docker-app

3️⃣ Open in browser
http://localhost:8080


You will see the webpage running inside a Docker container 🎉

🎯 What I Learned

Basics of Docker and containers

Writing a Dockerfile

Building Docker images

Running containers

Using Git and GitHub for version control

📌 Why This Project

I built this project as a starting point for DevOps and Cloud Engineering and to prepare myself for internship opportunities.

🙌 Author

Princi
Aspiring DevOps & Cloud Engineer
Beginner in Docker & DevOps