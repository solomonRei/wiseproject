# Wise: Rapid Video Summaries & Analytics

Wise by Team19 is an innovative tool designed for content creators and video enthusiasts. It offers rapid video summaries, tag analytics, viewership trends, and personalized content recommendations integrated with ChatGPT. Built using Spring Java, Flask Python, React JS, and an SQL database, Wise ensures an optimized experience for YouTube content, boosting engagement and performance.

## Table of Contents

- [About](#about)
- [Tech Stack Overview](#tech-stack-overview)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Authors](#authors)
- [Acknowledgements](#acknowledgements)

## About

Wise is crafted to revolutionize the way content is consumed and analyzed on YouTube. By providing quick video summaries and in-depth analytics, it saves users time while offering valuable insights into content trends and viewer preferences.

## Tech Stack Overview

Our project leverages various technologies, each chosen for its reliability and performance:

### Backend with Spring Java & Flask Python:
- [![Spring Java][spring_java_badge]][spring_java_link]: For robust backend functionality and application logic.
- [![Flask Python][flask_python_badge]][flask_python_link]: A micro web framework for efficient backend operations.

### Frontend with React.js:
- [![React JS][react_js_badge]][react_js_link]: Powers the interactive elements of our user interface.

### Database and Message Broker:
- [![SQL Database][sql_database_badge]][sql_database_link]: Reliable database management for storing and retrieving data.

### Containerization and Orchestration:
- [![Docker Compose][docker_compose_badge]][docker_compose_link]: For defining and running multi-container Docker applications.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Docker and Docker Compose for running the containerized applications.
- A modern web browser, preferably Google Chrome.

### Installation

1. **Clone the repository**

    ```bash
    git clone https://github.com/YourRepository/Wise.git
    ```

2. **Setting up the Services**
- Navigate to the project directory.
- Run the Docker Compose files to set up the PostgreSQL database, RabbitMQ, backend, and frontend services.

    ```bash
    docker-compose up
    ```

## Usage

After setting up the project, you can:

1. **Access Wise**: Open your browser and navigate to `http://localhost:3000`.
2. **Explore Features**: Check out video summaries, analytics, and personalized recommendations.

## Acknowledgements

- Thanks to all the open-source projects that made this application possible.

<!-- Badges -->
[spring_java_badge]: https://img.shields.io/badge/Spring_Java-6DB33F?style=plastic&logo=spring&logoColor=white
[flask_python_badge]: https://img.shields.io/badge/Flask_Python-000000?style=plastic&logo=flask&logoColor=white
[react_js_badge]: https://img.shields.io/badge/React_JS-20232A?style=plastic&logo=react&logoColor=61DAFB
[sql_database_badge]: https://img.shields.io/badge/SQL_Database-316192?style=plastic&logo=database&logoColor=white
[docker_compose_badge]: https://img.shields.io/badge/Docker_Compose-2496ED?style=plastic&logo=docker&logoColor=white

<!-- Links -->
[spring_java_link]: https://spring.io/projects/spring-framework
[flask_python_link]: https://flask.palletsprojects.com/
[react_js_link]: https://reactjs.org/
[sql_database_link]: https://www.mysql.com/
[docker_compose_link]: https://docs.docker.com/compose/
