# Docker Template for Django Project

Developed for help to create containerized projects using Docker with PostgreSQL as database and PgAdmin as data visualization.

## Installation
1. Install Docker and Docker Compose.
2. Clone this repository or fork this repository:
```bash
git clone https://github.com/heytorvas/template-django-docker.git
```
3. Change directory to repository:
```bash
cd template-django-docker
```
## Development Environment
1. Build the containers:
```bash
docker-compose build &
```
2. Up the containers:
```bash
docker-compose up db &
docker-compose up api &
```
3. It's possible up pgadmin container, if you want:
```bash
docker-compose up pgadmin &
```
## Notes
Run project: ```http://localhost:8000```