# Personal Trainer App

This is a Dockerized version of my personal trainer app.

## Links

- **Docker Hub Image**: [Personal Trainer App on Docker Hub](https://hub.docker.com/r/pr0fix/personaltrainerapp)
- **Project GitHub-Repository**: [Personal Trainer App on GitHub](https://github.com/pr0fix/personalTrainerApp)

## Docker Installation and Image Pull Instructions

### Prerequisites

- **Unix-based operating systems**: Install Docker using the following command:
  ```sh
  sudo apt install docker.io
  ```
- **Windows-based operating systems**: Install Docker Desktop from [Docker's official site](https://www.docker.com/products/docker-desktop/)

### Installation steps

1. Pull the Docker image:
  ```sh
  docker pull pr0fix/personaltrainerapp
  ```
2. Run the container:
  ```sh
  docker run -p 3000:3000 pr0fix/personaltrainerapp
  ```
4. Access app via browser:
   http://localhost:3000/personalTrainerApp/
