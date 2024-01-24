# Docker Compose Project With Multiple Containers

This project demonstrates the use of Docker Compose to create and manage two containers: one for an ExpressJs server and another for a Redis database. The ExpressJs server is a simple web application that displays the number of times the server has been visited. 🚀

## Prerequisites

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Project Structure

- **index.js**: ExpressJs server code.
- **package.json**: Node.js project configuration.
- **Dockerfile**: Dockerfile for building the ExpressJs server container.
- **docker-compose.yml**: Docker Compose configuration file.

## Running the Project

1. Clone the repository and Navigate to the project directory:

   ```bash
   git clone https://github.com/parasd086/Devops-SRE-Practice.git
   cd Devops-SRE-Practice/
   cd Docker-and-Kubernetes-Deep-Dive/
   cd Docker-Compose-With-Multiple-Local-Containers
   ```

2. Build and start the containers:

   ```bash
   docker-compose up --build
   ```

   This command will build the ExpressJs server container using the Dockerfile and start both the ExpressJs server and Redis containers.

3. Access the application:

   Open your browser and visit http://localhost:4001. You should see the number of visits displayed.

4. To stop the containers, use:

   ```bash
   docker-compose down
   ```

## Configuration

- **ExpressJs Server Configuration:**
  The ExpressJs server is configured in `index.js`. You can modify the server logic and settings in this file.

- **Docker Compose Configuration:**
  Docker Compose settings are defined in `docker-compose.yml`. You can adjust container names, ports, and other configurations as needed.

## Dependencies

- **Express:**
  Web application framework for Node.js.

- **Redis:**
  In-memory data structure store used for storing visit counts.

## Notes

- The Redis server container is named `redis-server` and is accessible from the ExpressJs server using this hostname.

## Contributions

Contributions, issues, and feedback are welcome! If you encounter any problems or have suggestions for improvements, please open an issue. Feel free to customize and expand upon this project as needed. Happy Dockerizing! 🐳✨

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/parasd086/Devops-SRE-Practice/blob/main/LICENSE) file for details.

---
