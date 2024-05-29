# Portainer Docker Compose

This repository contains a `docker-compose.yml` file to set up Portainer using Docker Compose.

## Prerequisites

- Docker installed on your machine.
- Docker Compose installed on your machine.

## Setup

1. Clone this repository or download the `docker-compose.yml` file.

2. Navigate to the directory containing the `docker-compose.yml` file.

3. Create a `.env` file in the same directory with the following content:

```bash
# .env
PORTAINER_HTTP_PORT=8000
PORTAINER_HTTPS_PORT=9443
```

4. Run the following command to start the Portainer service:

```bash
docker-compose up -d
```

## License
This project is licensed under the MIT License.

5. Access Portainer:
* HTTP: http://localhost:8000
* HTTPS: https://localhost:9443

## Environment Variables
The .env file contains the following environment variables:

* `PORTAINER_HTTP_PORT`: The HTTP port to access Portainer (default is 8000).
* `PORTAINER_HTTPS_PORT`: The HTTPS port to access Portainer (default is 9443).