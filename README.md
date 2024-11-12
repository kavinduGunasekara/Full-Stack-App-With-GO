🎬 Overview: This project walks you through building a full-stack application with a TypeScript-based frontend using Next.js, a Go backend, and a PostgreSQL database, all containerized with Docker.
🔍 Technology Setup: Initial setup requires Docker, Go, and a basic understanding of APIs. The developer sets up a Git repository and a .gitignore to exclude unnecessary files like Node modules.
🐳 Database Setup: PostgreSQL is installed as a Docker container with essential environment configurations, such as username and password. Persistent storage is ensured through Docker volumes.
📡 Backend with Go: The backend Go application includes defining a REST API with endpoints for CRUD operations. Gorilla Mux is used as a router, and PostgreSQL drivers are incorporated to connect with the database.
🎨 Frontend with Next.js: The Next.js frontend includes user components with Tailwind CSS for styling, Axios for HTTP requests, and dynamic form handling.
🧩 Containerized Deployment: The final step involves creating Docker files for the frontend, backend, and database, enabling seamless deployment with Docker Compose.
Insights Based on Numbers
🧮 Versioning: PostgreSQL version 13 is explicitly chosen, emphasizing stability in database support.
⚙️ Port Allocation: The backend API listens on port 8000, which is exposed in Docker for local testing and potential cloud deployment.
🔗 Data Persistence: Docker volumes named PG_data ensure that database data persists even when containers restart.

![Screenshot 2024-03-31 021857](https://github.com/kavinduGunasekara/Full-Stack-App-With-GO/assets/137909922/880122fd-c7a6-4cdd-9848-99de3faffb48)
![Screenshot 2024-03-31 021911](https://github.com/kavinduGunasekara/Full-Stack-App-With-GO/assets/137909922/68dd99a9-c215-4535-8024-a5cb1ddc28a3)


https://github.com/kavinduGunasekara/Full-Stack-App-With-GO/assets/137909922/31d86282-594d-4ae4-a635-078ddd89087a

