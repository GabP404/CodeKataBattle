# CodeKataBattle (CKB)

## Overview

**CodeKataBattle (CKB)** is a platform designed for students to practice coding collaboratively. It enables educators to create coding challenges, referred to as **Battles**, within **Tournaments** where students participate in teams. The platform automatically checks code submissions, assigning scores based on correctness, completion speed, and code quality. Instructors can also provide additional scores during a **Consolidation Stage** for each Battle. Students are ranked within tournaments and can earn **Badges** for achievements, making programming education more competitive and engaging.

## Features

- **Coding Battles**: Educators set up coding challenges for students to solve in teams.
- **Automated Scoring**: The system automatically evaluates code submissions based on several factors:
  - Correctness
  - Speed
  - Code quality
- **Consolidation Stage**: Educators can manually review submissions and provide additional scores.
- **Rankings and Badges**: Students are ranked in tournaments, and earn badges for achievements to encourage competition and make learning more engaging.
- **Team-Based Learning**: Students collaborate in teams to tackle coding problems and improve their coding skills through friendly competition.

## Documentation

This project follows a rigorous development process, and the following documents are provided to guide the design and implementation:

1. **Requirements Analysis and Specification Document (RASD)**: Describes the functional and non-functional requirements of the system, user stories, and use case diagrams.
2. **Design Document (DD)**: Includes architectural diagrams, design patterns, class diagrams, and component design details.
3. **Implementation and Testing Document (ITD)**: Outlines how the system was implemented, including testing strategies, unit tests, and integration tests.

## Technology Stack

The project utilizes a modern technology stack to ensure scalability, maintainability, and ease of deployment:

### Frontend:
- **React**: A JavaScript library for building user interfaces, used to create an interactive and responsive web platform for students and educators.

### Backend:
- **Java Spring Boot**: Provides the core application logic and handles business processes like challenge setup, team management, scoring, and consolidation.
- **Java Persistence API (JPA)**: Manages the persistence layer, interacting with the SQL database for storing user data, scores, and results.

### Database:
- **SQL Database**: Stores essential data such as users, teams, challenges, scores, and rankings.

### DevOps:
- **Docker**: Used to containerize the application, ensuring that the frontend, backend, and database run in isolated environments.
- **Kubernetes**: Manages the deployment, scaling, and orchestration of Docker containers, enabling smooth scaling and availability.
