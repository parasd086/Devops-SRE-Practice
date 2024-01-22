# Containerize Tiny ExpressJs Web Server

This project serves as a hands-on guide for learning the basics of Docker by creating a simple ExpressJs application, containerizing it, and accessing it through a browser on your local machine. 🚀

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed on your machine:

- [Docker](https://docs.docker.com/get-docker/)
- [ExpressJs](https://expressjs.com/)

### Build and Run the Docker Container

1. Clone this repository:

   ```bash
   git clone https://github.com/parasd086/Devops-SRE-Practice.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Devops-SRE-Practice/
   cd Docker-and-Kubernetes-Deep-Dive/
   cd Containerize-Simple-ExpressJs-Web-Server/
   ```

3. Build the Docker image:

   ```bash
   docker build -t my-username/tiny-express-app .
   ```

4. Run the Docker container:

   ```bash
   docker run -p 8080:8080 -d my-username/tiny-express-app
   ```

### Access the App on Browser

Open your browser and navigate to [http://localhost:8080](http://localhost:8080). You should see a simple "Hello, Docker!" message, indicating that the ExpressJs application is successfully running within the Docker container.

## Customization

Feel free to modify the ExpressJs application in the `index.js` file to suit your preferences. Update the `Dockerfile` if additional dependencies or configurations are needed.

## Contributions

Contributions, issues, and feedback are welcome! If you encounter any problems or have suggestions for improvements, please open an issue.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
