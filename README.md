# Multi-Container Application with Docker Compose

## Overview
This project demonstrates the orchestration of a multi-container application using Docker Compose. It includes:
- A **Node.js** backend service.
- A **MongoDB** database service.

## Skills Demonstrated
- Docker Compose orchestration
- Networking between containers
- Persistent storage with Docker volumes

## Project Structure
docker-compose-multi-container/
├── backend/
│   ├── app.js
│   ├── Dockerfile
│   ├── package.json
├── data/
├── docker-compose.yml


## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/multi-container-docker-project.git
   cd multi-container-docker-project
   
2. Build and start the containers:
   ```bash
   docker-compose up --build

3. Access the backend service at http://localhost:3000.
