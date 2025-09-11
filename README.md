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

## Project Goals

- **Learn Docker Basics**: Understand how to create and manage containers using Docker.
- **Explore Multi-Service Applications**: Gain insights into setting up and running front-end and back-end services.
- **Master Docker Compose**: Learn how to orchestrate multiple services efficiently.
- **Enhance Development Workflow**: Utilize Docker to streamline development and deployment processes.

Thanks!