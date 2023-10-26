# Classwork Assignment 1

This classwork assignment is not part of the grading for the Modern DevOps Practices course but it is meant to provide additional hands-on practice.

You are given a Python application and a client has requested your help to run it in a Docker container and automate the process of building the Docker image.

## Start up

Install necessary dependencies

```bash
pip3 install src/requirements.txt
```
Start the application

```bash
python3 src/app.py
```

## Tasks
- Create a new **public** repository and use this one as a template.
- Containerize the Python application in the `src/` directory. Create a Dockerfile and push it in your repository.
- Create a GitHub Actions workflow that builds the Docker image and publishes it to your personal DockerHub account on every push to the main branch.
- Submit a link to your repository in the open Moodle assignment.

### Bonus
- Optimize the size of the Docker image. Use a more minimal base image.