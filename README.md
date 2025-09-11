![Docker project](https://github.com/user-attachments/assets/03cba098-6d44-4975-a32a-557f05899b8f)
## Introduction

Docker Project! This repository is a comprehensive collection of tasks designed to explore and utilize Docker in various environments. The project aims to provide a deep understanding of how to build and manage containers using Docker, as well as orchestrate multi-service applications with Docker Compose.

## Repository Structure

### Tasks Overview:

- **task0**: Contains a basic Dockerfile to demonstrate the creation of a simple Docker image.
- **task1**: Includes an `api.py` file and a Dockerfile to run a basic API application.
- **task2**: Features separate Dockerfiles for the back-end and front-end setups, showcasing a multi-service architecture.
- **task3**: Similar to task2 but with additional improvements and optimizations.
- **task4**: Introduces a `compose.yml` file to coordinate services using Docker Compose.
- **task5**: Adds a proxy setup with Dockerfiles and a `compose.yml` file for advanced service orchestration.
- **task6**: Demonstrates advanced configurations, including support for multiple API servers and a proxy layer.

## How to Use

1. **Install Prerequisites**:
   - Ensure Docker and Docker Compose are installed on your system.

2. **Navigate to the Desired Task**:
   ```bash
   cd taskX
   ```
   Replace `X` with the task number you want to explore.

3. **Build and Run Services**:
   ```bash
   docker compose up
   ```

4. **Access the Application**:
   Open your browser and navigate to `http://localhost` to interact with the application.
