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

### Screenshots

- **Docker Compose Setup:**
  ![Docker Compose]![docker-compose](https://github.com/user-attachments/assets/84aa59ec-a533-40c1-8b1f-6a0d36db349b)

- **Running Containers:**
  ![Docker Containers]![Running-Containers](https://github.com/user-attachments/assets/6e3ceb2b-dace-49e9-bc64-5e997eeb290b)


- **Backend Service Output:**
  ![Backend Output]![webserver-running](https://github.com/user-attachments/assets/0d08cc29-addf-450a-aa3d-b406cf8d7f3d)

