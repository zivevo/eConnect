
# Central Repository eConnect

Welcome to the **[eConnect]** central repository. This repository serves as the primary hub for managing, organizing, and linking various repositories associated with the project.

---

## Table of Contents
- [Structure](#structure)
- [Getting Started](#getting-started)

---

## Structure

The central repository is structured as follows:

- **Frontend**  
   Contiains files related to the frontend of the app, as well as the dockerfile of how to start it

- **Backend**  
   Contiains files related to the backend of the app, as well as the dockerfile of how to start it

- **Docker Compose**  
   The main starting point of the docker containers

---

## Getting Started

1. **Clone this repository**  
   ```bash
   git clone https://github.com/your-organization/central-repo.git
   ```

2. **[eConnect-Backend]** - Clone the backend in to the central repo.
   ```bash
   git clone https://github.com/zivevo/eConnect-backend.git backend
   ```

3. **[eConnect-Frontend]** - Clone the backend in to the central repo.
   ```bash
   git clone https://github.com/zivevo/eConnect-frontend.git frontend
   ```

3. **Run the docker environment**
   1. *Have Docker Desktop Installed*
   2. Install dependency images:
   ```bash
   docker pull node  
   docker pull oven/bun  
   ```
   2. First time start: 
   ```bash   
   docker-compose up -d --build
   ```
   3. Normal start:
   ```bash   
   docker-compose up -d
   ```
   4. Stop containers:
   ```bash   
   docker-compose down
   ```
---

###  More info on Notion!