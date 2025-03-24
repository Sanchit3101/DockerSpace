🐳 DOCKER BASICS

Welcome to Docker Basics! 🚀 In this project, I started by running a simple "Hello, World!" program inside a Docker container. This guide will walk you through setting up a basic Dockerized Python application from scratch.

📂 Creating the Application File

First, create a Python file named app.py with the following content:

print("Hello, World!")

📖 Helpful Resources

Here are some useful references to get you started with Docker:🔹 Official Docker Documentation🔹 Docker Desktop Guide

🚀 How to Deploy Your Application

Follow these steps to containerize and run your Python application using Docker:

🔹 Step 1: Install Docker and Python

1️⃣ Download and install Docker Desktop → Download here2️⃣ Ensure Docker is up and running.3️⃣ Install Docker and Python extensions in your development environment.

🔹 Step 2: Verify Installation

Before moving forward, confirm that Docker and Python are installed properly:

✅ Check Docker version:

docker --version

✅ Check Python version:

python --version

If both commands return valid versions, you’re all set! 🎉

🔹 Step 3: Build & Run Your Dockerized Application

🛠️ i) Build the Docker Image

Run the following command to build your Docker image:

docker build -t myapp .

🔍 ii) Verify the Image Creation

Check if your Docker image was created successfully:

docker images

▶️ iii) Run the Docker Container

Execute the container to print "Hello, World!" in the console:

docker run myapp

🎯 Wrapping Up

This guide provides a simple and structured way to run your first Dockerized Python application. 🐳✨

🔹 What's next? Dive into Docker volumes, networking, and multi-container applications! 💡

🚀 Happy Docking! ⚓🌊

