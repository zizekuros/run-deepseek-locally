# Run DeepSeek locally with Docker

## Introduction
This repository provides a simple setup to run the **DeepSeek-R1 model** locally using **Ollama**, along with **Open WebUI** to interact with the model via a web interface.

## Prerequisites
- Docker installed on your system
- Docker Compose installed

## How to Run It
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
   - Pull and run the **DeepSeek-R1 model** using Ollama.
   - Launch **Open WebUI** for easy interaction.

## How to Open Web UI
Once running, open your browser and go to:
```
http://localhost:3000
```
From there, you can interact with the DeepSeek model through a user-friendly web interface.

## How to Stop Service
To stop the services, run:
```sh
docker-compose down
```
This will shut down both Ollama and Open WebUI while preserving your downloaded model and settings.

## Congratulations 🎉
You have successfully set up a local AI environment with **Ollama** and **Open WebUI**! Enjoy interacting with your model locally and efficiently. 🚀
