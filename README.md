
# Password Manager Project

## Introduction

This project involves implementing a password manager with integrated DevSecOps practices. This README will guide you through cloning the repository, setting up the application with Docker Compose, and verifying that it is running correctly.

## Prerequisites

Before you begin, ensure you have the following installed on your machine:

- Git
- Docker
- Docker Compose

## Cloning the Repository

To get started, clone the repository to your local machine using the following command:

```bash
git clone git@github.com:Jose05102/Final-password-manager.git
```

This command will create a local copy of the repository on your machine.

## Setting Up with Docker Compose

Navigate to the directory containing the cloned repository:

```bash
cd Final-password-manager
```

To set up the application, use Docker Compose to build and start the Docker containers. Run the following command:

```bash
docker-compose up --build -d
```

This command will build the Docker images and start the containers as defined in the `docker-compose.yml` file. The `--build` flag ensures that the images are built from scratch, incorporating any changes to the code.

## Verifying the Application

Once Docker Compose has finished setting up the containers, you can verify that the application is running by accessing it via your web browser. Open a browser and navigate to:

```
http://localhost:80
```

Replace `8000` with the appropriate port if it has been configured differently in your `docker-compose.yml` file.

## Troubleshooting

- If you encounter issues with Docker Compose, you can check the logs for errors by running:

  ```bash
  docker-compose logs
  ```

- Ensure Docker and Docker Compose are correctly installed and running on your system.

- If the application does not appear in your browser, confirm that Docker Compose has completed the setup and that there are no errors in the logs.

## Stopping the Application

To stop the Docker containers and remove them, run:

```bash
docker-compose down
```

This will stop and remove all containers defined in the `docker-compose.yml` file.

## Conclusion

By following these steps, you should be able to clone the repository, set up the password manager with Docker Compose, and verify that it is running correctly. This process demonstrates the integration of DevSecOps practices into the development workflow, ensuring a secure and efficient application.

---
