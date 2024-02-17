# ReactCanvas CI/CD: Dockerized Create-React-App with Travis CI and AWS Elastic Beanstalk

Welcome to ReactCanvas CI/CD, a project that combines the power of React, Docker, and a seamless Continuous Integration/Continuous Deployment (CI/CD) pipeline. This repository demonstrates the containerization of a default React application created with "create-react-app." Leveraging Docker, Nginx, Travis CI, and AWS Elastic Beanstalk, the project automates the deployment process, making it easier for developers to manage, test, and deploy their React applications.

## Prerequisites

Before you start working with this project, ensure that you have the following tools and accounts set up:

- [Node.js](https://nodejs.org/)

- [Docker](https://www.docker.com/)

- [Travis CI](https://travis-ci.org/)

- [AWS](https://aws.amazon.com)

## Local Build And Setup:

Follow these steps to clone and set up the project on your local machine:

1.  Clone the Repository:

    ```bash
    git clone https://github.com/your-username/project-name.git
    ```

2.  Navigate to the Project Directory:

    ```bash
    cd Devops-SRE-Practice/
    cd Docker-and-Kubernetes-Deep-Dive/
    cd Containerize-React-Docker-Nginx-Travis-AWS/
    ```

3.  Build and Run the Development Version:
    Launch the development version of the application with:

        ```bash
        docker-compose -f docker-compose-dev.yml up --build
        ```

    Access the application at http://localhost:3000. Docker Compose automatically runs tests during setup.

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/parasd086/Devops-SRE-Practice/blob/main/LICENSE) file for details.

---
