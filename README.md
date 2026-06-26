Eccolo corretto, senza riferimento alla demo, tutto in un unico box copiabile:

# METROFOOD-IT Access Portal

The **METROFOOD-IT Access Portal** is a web-based platform developed to support access to the METROFOOD-IT research infrastructure and to facilitate the interaction between stakeholders of the agri-food sector and the services offered by the project.

The portal provides a virtual space where users can stay informed about open calls and participate in access opportunities related to **Transnational Access (TNA)** and **Virtual Access (VA)**.

## Project Context

The Access Portal is part of the **METROFOOD-IT** project:

**METROFOOD-IT - Strengthening of the Italian Research Infrastructure for Metrology and Open Access Data in support to the Agrifood**

The platform is related to **WP5 – Activity A5.3**, which focuses on the implementation of access services to the infrastructure.

The Access Portal has been implemented by the **University of Molise (UNIMOL)**.

## Access Link

The current access endpoint is:

```text
http://193.205.105.129
```

> Note: the IP address `193.205.105.129` is currently used as the access endpoint and may be updated in future deployments.

## Objectives

The Access Portal aims to:

- Provide a complete web portal for managing and supporting access to METROFOOD-IT services;
- Support stakeholders in participating in open calls;
- Promote the use of Transnational Access and Virtual Access opportunities;
- Facilitate interaction between METROFOOD-IT and potential users;
- Contribute to the operational implementation of METROFOOD-IT as a service-oriented research infrastructure.

## Main Features

The platform allows users and stakeholders to access information and services related to METROFOOD-IT.

Main features include:

- Information about open calls;
- Support for Transnational Access (TNA);
- Support for Virtual Access (VA);
- Information about training opportunities;
- Information about facilities and available services;
- Information about the METROFOOD-IT project and consortium;
- User-oriented access to resources and project opportunities.

## Platform Overview

The Access Portal acts as a central entry point for stakeholders interested in the METROFOOD-IT infrastructure.

```text
Stakeholders / Users
        |
        v
METROFOOD-IT Access Portal
        |
        v
Open Calls, TNA, VA, Training, Facilities, Project Information
```

The portal supports the METROFOOD-IT mission by helping users take advantage of the opportunities offered by the infrastructure and by promoting research, innovation, and technology transfer in the agri-food sector.

## Architecture

A possible deployment architecture is shown below:

```text
User Browser
    |
    v
Access Portal Frontend
    |
    v
Backend Services / APIs
    |
    v
Database and METROFOOD-IT Services
```

The final architecture may include frontend components, backend services, authentication mechanisms, and data storage services depending on the deployment configuration.

## Technologies

The project may include the following technologies:

- Web frontend application;
- Backend API services;
- Authentication and access management;
- Database service;
- Docker-based deployment;
- Remote server hosting.

Further technical details will be added according to the final implementation.

## Repository Structure

A possible repository structure is:

```text
.
├── frontend/              # Access Portal frontend application
├── backend/               # Backend services and APIs
├── docker-compose.yml     # Docker deployment configuration
├── README.md              # Project documentation
└── .env.example           # Example environment variables
```

The structure may change according to the final organization of the project.

## Getting Started

Clone the repository:

```bash
git clone <repository-url>
cd <repository-name>
```

Install the dependencies for each component.

For the frontend:

```bash
cd frontend
npm install
npm start
```

For the backend:

```bash
cd backend
npm install
npm start
```

## Docker Deployment

If Docker is used, the project can be started with:

```bash
docker compose up --build
```

To run the services in detached mode:

```bash
docker compose up -d --build
```

To stop the services:

```bash
docker compose down
```

## Environment Configuration

The project may require environment variables for service ports, database access, authentication, and deployment configuration.

Example:

```env
PORT=3000
DB_HOST=localhost
DB_PORT=27017
DB_NAME=MetroUsers
DB_USER=your_db_user
DB_PASSWORD=your_db_password
JWT_SECRET=your_secret_key
```

Do not commit real credentials, passwords, tokens, or production secrets to the repository.

## Deployment Information

Current access endpoint:

```text
http://193.205.105.129
```

If the portal is exposed on a specific port, use:

```text
http://193.205.105.129:<PORT>
```

Examples:

```text
http://193.205.105.129:4200
```

```text
http://193.205.105.129:3000
```

## Status

This README is a preliminary version and will be updated with:

- Final deployment instructions;
- Complete architecture description;
- API documentation;
- Screenshots of the Access Portal;
- Authentication and access control details;
- Production endpoint;
- License information.

## Acknowledgements

This work is related to the METROFOOD-IT project and to the implementation of the Access Portal within WP5 – Activity A5.3.

## License

License information will be added in a future version.
