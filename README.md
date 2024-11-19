# Palmetto Weather App

This repository contains a monorepo for the **Palmetto Weather App**, a weather application built using React and NestJS. The app is containerized with Docker for simplified deployment.

## Prerequisites

Ensure you have the following installed:
- Node.js (v18 or later) and npm
- React.js
- Docker and Docker Compose
- NestJS CLI (`npm install -g @nestjs/cli`)

---

## Setup Instructions

### 1. Clone the main Repository
Clone this repository to your local machine and navigate to the working directory.

```bash
git clone <repository-url>
cd palmetto-weather

```
### 2. Clone the Frontend Repository

Navigate to the `palmetto-weather-app` directory and clone the frontend repository:

```bash
cd palmetto-weather-app
git clone https://github.com/kvrivas854/palmetto-weather-app.git .
npm install
```
### 3. Clone the Backend Repository

Navigate to the `palmetto-weather-app` directory and clone the frontend repository:

```bash
cd ../weather-api
git clone https://github.com/kvrivas854/weather-api.git .
npm install
```
### 4. Build the Docker Containers

To build the application containers, navigate to the palmetto-weather-container folder containing the `docker-compose.yml` file and run:

```bash
cd palmetto-weather-container
docker-compose build
docker-compose up




