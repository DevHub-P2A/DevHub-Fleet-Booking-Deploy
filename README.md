# DevHub Fleet Booking

This repository is responsible for bringing together all the services and components of the **DevHub Fleet Booking** project.

It pulls the required images from the individual service repositories and uses Docker Compose to run the complete application as a single environment.

## What You'll Find Here

- **Docker Compose configuration**
  - Responsible for pulling and running the required Docker images.
  - Connects the different services together.
  - Provides the configuration needed to run the complete application.

## How It Works

Each service is maintained in its own repository. This repository acts as the **main deployment and orchestration repository**, bringing all the services together using Docker Compose.

```text
Individual Service Repositories
          │
          ▼
     Docker Images
          │
          ▼
   Docker Compose
          │
          ▼
 DevHub Fleet Booking
```

## Running the Application

Make sure Docker and Docker Compose are installed, then run:

```bash
docker compose up -d
```

To stop the application:

```bash
docker compose down
```
