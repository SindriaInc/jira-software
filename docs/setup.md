# Docs

## Setup

### Standard install

- On your host make a directory: `mkdir -p jira`
- Move into it: `cd jira`
- Go to under deployments [folder](https://github.com/SindriaInc/jira-software/tree/master/deployments)
- Setup file env: `cp .env.example .env`
- Setup Docker Compose `cp docker-compose.example.yml docker-compose.yml`
- Run: `docker-compose up -d`
- Url: [http://localhost:8080](http://localhost:8080)
