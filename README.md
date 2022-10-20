# Fibonacci-in-overcomplicated-way-with-docker

This project was done to learn docker.
Multi-container application.

```mermaid
graph LR;
    Nignx-->Express-Server;
    Nignx-->React-Server;
    Nignx-->CUSTOMER;
    React-Server-->Express-Server;
    Express-Server-->Redis;
    Express-Server-->Postgres;
    Redis-->Worker;
    Worker-->Redis;
```

### Developed using:
* <a href="https://kubernetes.io/"> ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5.svg?style=for-the-badge&logo=Kubernetes&logoColor=white) </a>
* <a href="https://www.w3schools.com/js/"> ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E.svg?style=for-the-badge&logo=JavaScript&logoColor=black) </a>
* <a href="https://www.docker.com/">  ![Docker](https://img.shields.io/badge/Docker-2496ED.svg?style=for-the-badge&logo=Docker&logoColor=white) </a>

