# Human Resources Application

This repository contains the files necessary to deploy the Human Resources application using Docker Compose. The application is divided into two submodules: `human-resources-app` and `human-resources-spring`, and a MySQL database.

## Project Structure

- **human-resources-app**: Contains the main application.
- **human-resources-spring**: Contains the backend of the application.
- **mysqlserver_data**: Data volume for the MySQL database.
- **docker-compose.yml**: Docker Compose configuration file.

## Prerequisites

Before starting, make sure you have the following programs installed on your system:

- Docker
- Docker Compose
- Git

## Setup Instructions

### Clone the Repository

Clone this repository and its submodules using the following command:

```bash
git clone --recurse-submodules <REPOSITORY_URL>
````

Docker Compose Configuration
The docker-compose.yml file contains the necessary configuration to deploy the application and the MySQL database.

Environment Variables
Make sure to set up the necessary environment variables for your application in the corresponding .env files in each submodule, if needed.
