# Week 1: Docker

## Activity 1: Getting Started with Docker
**Goal:** Understand the basics of Docker and containerization.
**Description:** Introduction to Docker, installation, and fundamental concepts.

**Tasks:**
1. Install Docker on your local machine.
2. Pull and run a simple Docker image (e.g., hello-world).
3. Explore basic Docker commands: `docker run`, `docker ps`, `docker stop`, `docker rm`.
4. Create and run a custom Docker container from a Dockerfile.
5. Push a custom Docker image to Docker Hub.

**References:**
- [Docker Documentation](https://docs.docker.com/)
- [Docker Hub](https://hub.docker.com/)
- [Dockerfile Reference](https://docs.docker.com/engine/reference/builder/)

## Activity 2: Working with Docker Compose
**Goal:** Manage multi-container applications using Docker Compose.
**Description:** Introduction to Docker Compose and its use cases.

**Tasks:**
1. Install Docker Compose.
2. Write a `docker-compose.yml` file to define a multi-container application (e.g., web app with a database).
3. Use `docker-compose up` to start the application.
4. Experiment with `docker-compose down` and `docker-compose logs`.
5. Scale services using `docker-compose scale`.

**References:**
- [Docker Compose Documentation](https://docs.docker.com/compose/)
- [Compose File Reference](https://docs.docker.com/compose/compose-file/)

## Activity 3: Docker Networking and Volumes
**Goal:** Understand Docker networking and persistent storage.
**Description:** Learn how to manage container networking and volumes.

**Tasks:**
1. Explore Docker networking commands: `docker network ls`, `docker network create`, `docker network connect`.
2. Create and connect containers to custom networks.
3. Use Docker volumes to persist data.
4. Mount a host directory as a data volume.
5. Backup and restore Docker volumes.

**References:**
- [Docker Networking](https://docs.docker.com/network/)
- [Docker Volumes](https://docs.docker.com/storage/volumes/)

## Activity 4: Dockerizing Applications
**Goal:** Containerize a sample application.
**Description:** Convert an existing application to run inside Docker containers.

**Tasks:**
1. Choose a simple web application (e.g., Node.js, Python).
2. Write a Dockerfile to containerize the application.
3. Build and run the containerized application.
4. Expose the application on a specific port.
5. Optimize the Dockerfile for smaller image size and better performance.

**References:**
- [Dockerfile Best Practices](https://docs.docker.com/develop/develop-images/dockerfile_best-practices/)
- [Node.js Docker Image](https://hub.docker.com/_/node)
- [Python Docker Image](https://hub.docker.com/_/python)
