<<<<<<< HEAD
# Two-Tier-Messaging-app-
A fully containerized two-tier messaging web application built with Flask. The primary focus of this project is on containerization and automated CI/CD using GitHub Actions. It features Docker Compose for service orchestration and robust deployment pipelines for seamless integration and delivery.
=======
# Two-Tier Messaging Web Application

## Introduction
This project demonstrates a modern approach to web application development and deployment using DevOps best practices. It is a messaging platform built with Flask, designed with a two-tier architecture and fully containerized for portability and scalability. Automated CI/CD pipelines are implemented using GitHub Actions to ensure reliable integration and delivery.

## Architecture
- **Two-Tier Design:**
  - **Web Tier:** Flask-based frontend and backend logic for handling user interactions and messaging.
  - **Database Tier:** Stores messages and user data, managed via SQL scripts and integrated with the web tier.
- **Containerization:**
  - Each tier runs in its own Docker container, managed by Docker Compose for easy orchestration and scaling.

## Key Features
- User messaging functionality
- Separation of concerns between web and database layers
- Dockerized services for consistent environments
- Automated build, test, and deployment workflows with GitHub Actions
- Scalable and maintainable project structure

## Technologies
- Python (Flask)
- Docker & Docker Compose
- GitHub Actions (CI/CD)
- SQL (message storage)

## Setup & Usage
### Prerequisites
- Docker
- Docker Compose
- Git

### Steps
1. Clone the repository:
   ```bash
   git clone <your-repo-url>
   cd <repo-directory>
   ```
2. Build and start the application:
   ```bash
   docker-compose up --build
   ```
3. Open your browser and go to `http://localhost:5000` to use the app.

## CI/CD Automation
- All code changes are automatically tested, built, and deployed using GitHub Actions.
- The pipeline ensures code quality, security, and fast delivery to production or staging environments.

## Project Structure
```
app.py               # Flask application
compose.yaml         # Docker Compose configuration
Dockerfile           # Container build instructions
message.sql          # Database schema and setup
requirements.txt     # Python dependencies
diagrams/            # Architecture and workflow diagrams
templates/index.html # Frontend template
```

## Contribution
Contributions, bug reports, and feature requests are welcome. Please open issues or submit pull requests for improvements.

## License
This project is licensed under the MIT License.
>>>>>>> c42b6a2 (Deploy V:1.0.1)
