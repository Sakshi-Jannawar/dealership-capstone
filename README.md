# Full-Stack Car Dealership Web Application

A comprehensive, responsive multi-tier car dealership web application built as part of the Full-Stack Developer Capstone Project. The application enables users across the United States to browse nationwide dealership branches, filter by state, review vehicle ratings and details, and submit reviews with integrated sentiment analysis.

## Project Architecture
The platform is built using a microservices-based design:
- **Frontend Layer:** Responsive single-page interface developed using React.js and styled with Bootstrap 5.
- **Web & Authentication Service:** Django application managing user registration, authentication sessions, and persistent vehicle database models (Car Make and Car Model) stored in SQLite.
- **Dealership & Review Microservice:** Node.js Express service backed by MongoDB handling dealership records and customer review submissions.
- **Sentiment Analysis Microservice:** Python Flask microservice using natural language processing (NLP) to categorize customer reviews into positive, neutral, or negative sentiments.
- **DevOps, CI/CD & Deployment:** Continuous Integration pipeline with GitHub Actions, containerization using Docker, orchestration with Kubernetes, and cloud deployment on IBM Cloud Code Engine.

## Tech Stack
- **Frontend:** React, HTML5, CSS3, JavaScript (ES6+), Bootstrap
- **Backend Frameworks:** Django, Node.js, Express.js, Flask
- **Databases:** SQLite, MongoDB
- **Cloud & Containerization:** Docker, Kubernetes, IBM Cloud Code Engine
- **CI/CD:** GitHub Actions (Flake8 linting and automated test runs)

## Author
Cars Dealership Engineering Team
