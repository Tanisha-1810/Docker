Hello World Docker Project


📌 Overview

This is a simple Python-based "Hello World" application containerized using Docker.

The project demonstrates how to:

-Write a basic Python script (hello.py)

-Create a Dockerfile to package it into a Docker image

-Build the Docker image:

 docker build -t kitz18/first_image:latest .

-Run the Docker Container

 docker run kitz18/first_image:latest 

-Push the image to Docker Hub for public use 

Login: docker login

Push to Docker Hub : docker push kitz18/first_image:latest 


<img width="1875" height="809" alt="image" src="https://github.com/user-attachments/assets/54915af5-9a86-4e39-bdec-b8e279a62a0c" />



🎯 Concepts Learned

Docker Basics: Images, containers, Dockerfile, build context

Python Execution Inside a Container

Pushing Images to Docker Hub

Tagging and Versioning Docker Images
