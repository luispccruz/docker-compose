# Docker Compose Files

This repository is a development lab to facilitate API testing in development environments. It contains several pre-configured Docker Compose files for different testing scenarios.

## Prerequisites

- Docker installed on your system. [Docker Installation](https://docs.docker.com/get-docker/)
- Docker Compose installed on your system. [Docker Compose Installation](https://docs.docker.com/compose/install/)

## Usage

1. Clone this repository to your local environment:

   ```bash
   git clone https://github.com/your-username/dev-lab-api.git

2. Navigate to the project directory:

    ```bash
    cd dev-lab-api

3. Choose the Docker Compose file that corresponds to the testing scenario you want to run.

    ```bash
    docker-compose up

4. Check the application that you run

Available Docker Compose Files
- MongoDB
- MySQL
- RabbitMQ

## Configuration

All projects have a .env file that you can change de volume, port etc of each application.

License
This project is licensed under the MIT License.
