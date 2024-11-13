# Full-Stack Application with Go, Next.js, and PostgreSQL

## Overview 🎬
This project guides you through building a full-stack application with a TypeScript-based frontend using Next.js, a Go backend, and a PostgreSQL database. The entire stack is containerized with Docker for streamlined deployment and scalability.

---

## Technology Stack 🔍
- **Frontend**: Next.js with TypeScript, styled with Tailwind CSS.
- **Backend**: Go, with Gorilla Mux for routing and PostgreSQL as the database.
- **Database**: PostgreSQL, containerized with Docker for ease of deployment.
- **Deployment**: Docker and Docker Compose for multi-container orchestration.

---

## Getting Started

### Prerequisites
1. **Docker** - To containerize and deploy each service.
2. **Go** - Backend API is built with Go.
3. **Git** - Initialize a repository and configure `.gitignore` to exclude unnecessary files (e.g., `node_modules/`).

---

## Database Setup 🐳
1. **PostgreSQL**: Set up as a Docker container with environment variables for credentials:
   - Username
   - Password
2. **Persistent Storage**: Use Docker volumes (e.g., `PG_data`) to ensure data persists between container restarts.

---

## Backend with Go 📡
The Go application handles API requests and connects with PostgreSQL:
- **Framework**: Gorilla Mux is used for routing.
- **Database Connectivity**: PostgreSQL drivers are incorporated to enable CRUD operations.

---

## Frontend with Next.js 🎨
The Next.js frontend includes:
- **UI Components**: Styled with Tailwind CSS.
- **Data Handling**: Axios for making HTTP requests to the Go API.
- **Dynamic Forms**: Managed to enhance user interaction.

---

## Containerized Deployment 🧩
Each component (frontend, backend, database) is containerized for deployment using Docker Compose:
1. **Frontend** and **Backend** Dockerfiles specify configurations for deployment.
2. **Docker Compose** orchestrates container startup and network configuration.

---

## Additional Insights

### Versioning 🧮
- PostgreSQL version **13** is used for compatibility and stability.

### Port Allocation ⚙️
- The backend API listens on **port 8000**, which is exposed in Docker for testing and deployment.

### Data Persistence 🔗
- Database data is stored in Docker volumes (e.g., `PG_data`) to ensure persistence.

---

## Screenshots

![Application Screenshot 1](https://github.com/kavinduGunasekara/Full-Stack-App-With-GO/assets/137909922/880122fd-c7a6-4cdd-9848-99de3faffb48)
![Application Screenshot 2](https://github.com/kavinduGunasekara/Full-Stack-App-With-GO/assets/137909922/68dd99a9-c215-4535-8024-a5cb1ddc28a3)

---

## Demo Video
[![Demo Video](https://github.com/kavinduGunasekara/Full-Stack-App-With-GO/assets/137909922/31d86282-594d-4ae4-a635-078ddd89087a)](https://github.com/kavinduGunasekara/Full-Stack-App-With-GO/assets/137909922/31d86282-594d-4ae4-a635-078ddd89087a)
