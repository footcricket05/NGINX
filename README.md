# 📝 Simple Notes App Using NGINX for DevOps

A streamlined notes application developed with a modern tech stack, featuring React for the frontend and Django for the backend, and seamlessly integrated with NGINX as a reverse proxy.

## 📋 Requirements

To set up and run this application, you will need:

1. 🐍 Python 3.9
2. 🌐 Node.js
3. ⚛️ React

## 🚀 Installation

To get started with the Simple Notes App, follow these steps:

1. **Clone the Repository**

    ```bash
    git clone https://github.com/LondheShubham153/django-notes-app.git
    ```

2. **Build the Application**

    Navigate to the cloned directory and build the Docker image:

    ```bash
    docker build -t notes-app .
    ```

3. **Run the Application**

    Start the application by running the Docker container:

    ```bash
    docker run -d -p 8000:8000 notes-app:latest
    ```

## 🔄 NGINX Integration

To make the application publicly accessible, set up NGINX as a reverse proxy:

1. **Update System Repositories**

    ```bash
    sudo apt-get update
    ```

2. **Install NGINX**

    ```bash
    sudo apt install nginx
    ```

📌 **Note**: Further configuration details for NGINX to work with the notes app will depend on your specific setup and requirements.

