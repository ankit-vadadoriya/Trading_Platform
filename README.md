# Trading_Platform

## Project Overview

The Treading Platform is a web application that enables users to view, analyze, and interact with trending data. Designed with a robust backend powered by Java Spring Boot and a dynamic frontend created using React, this project highlights the integration of a RESTful API with a modern, responsive user interface.

The platform includes key features like trend visualization, user authentication, and data persistence, providing a seamless and secure experience for users. The backend leverages Spring Boot’s capabilities to handle complex business logic and ensure secure data transactions, while the React frontend focuses on delivering a smooth and engaging user experience.

## Project Structure

### Backend (Backend-Spring boot)

- RESTful API to handle data requests and responses.
- Uses Spring Security for managing authentication and authorization.
- Database: PostgreSQL with JPA and Hibernate ORM for seamless data management.
- Configurations handled in application.properties.

The backend is built with **Java Spring Boot** and is responsible for handling business logic, managing user data, and ensuring secure transactions. 
- **Key files include:**
- **`Backend/src/main/java/com/example/demo`**: Contains the core backend files, including controllers, services, and models.
- **`Backend/src/main/resources/application.properties`**: Configuration file for setting up database connections, server properties, etc.

### Frontend (Frontend-React)

- Uses functional components for improved performance and modularity.
- Axios is used to make HTTP requests to the backend API.
- Styled with CSS and Bootstrap for a visually appealing, user-friendly interface.

The frontend is developed using **React** for a responsive and interactive user experience. 
- **Key files include:**
- **`Frontend/src/App.js`**: Main component that acts as the entry point for rendering the application's user interface.
- **`Frontend/src/index.js`**: Renders the app and integrates with the React DOM.

## Setup

### Prerequisites
- **Java 11** or newer
- **Node.js and npm**
- **MySQL Database** (or another compatible database)
