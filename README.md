## What is Docker
Docker is a tool that lets you package your app and all its dependencies into a container, so it runs the same anywhere—your laptop, server, or cloud.

## Problems Docker Solves
1. "Works on my machine" – Same environment everywhere.
2. Dependency conflicts – Each app has its own isolated setup.
3. Complex setup – Easy to run multi-service apps.
4. Slow deployments – Fast and consistent with containers.
5. Heavy VMs – Containers are lightweight and efficient.
6. Hard to replicate environments – Easy with Docker images.

## Docker Concepts
Here are the core concepts you need to understand Docker:

### 1. Image 🧱
- A Docker image is a blueprint for your app.
- It’s a read-only file with everything needed to run: code, libraries, settings.
- Think of it like a recipe.

### 2. Container 📦
- A Docker container is a running instance of an image.
- It’s a live, lightweight, and isolated environment where your app runs.
- Think of it like the dish made from the recipe.

### 3. Dockerfile 📝
- A script that defines how to build a Docker image.
- Like a recipe for the image.

### 4. Volumes 💾
- Persistent storage for containers.
- Used to save data even if the container is deleted.

### 5. Networks 🌐
- Allows containers to talk to each other securely.

### 6. Docker Compose 📂
- Tool to run multi-container apps using a simple YAML file.
- Good for apps with services like web + database.

