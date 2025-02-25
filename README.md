# Run DeepSeek locally with Docker

## Introduction
This repository provides a simple setup to run the **DeepSeek R1 models** locally using **Ollama**, along with **Open WebUI** to interact with the model via a web interface.

## Prerequisites
- Docker installed on your system
- Docker Compose installed

## How to Start the Service
1. Clone this repository:
   ```sh
   git clone <repository_url>
   cd <repository_folder>
   ```
2. Start the services:
   ```sh
   docker-compose up -d
   ```
   This will:
   - Pull and run Ollama container with two **DeepSeek-R1 models (1.5b and 8b)** pre-installed.
   - Pull and run  **Open WebUI** container for easy interaction with the model.

   **NOTE:** 
    The DeepSeek r1 models (1.5b and 8b) must be downloaded inside the Ollama container, and it might take some time until the services are fully running if the Ollama and Open-WebUI Docker images are being pulled and downloaded for the first time.

## How to Open WebUI
Once running, open your browser and go to:
```
http://localhost:8888
```
From there, you can interact with the DeepSeek model through a user-friendly web interface. The first time you log in, the system will prompt you to register an admin user by providing a name, email, and password. After that, you can interact with the DeepSeek model through a user-friendly web interface.

## How to Stop Service
To stop the services, run:
```sh
docker-compose down
```
This will shut down both Ollama and Open WebUI while preserving your downloaded model and settings.

## Congratulations 🎉
You have successfully set up a local AI environment using **Ollama** and **Open WebUI**! Enjoy interacting with your model locally and efficiently. 🚀
