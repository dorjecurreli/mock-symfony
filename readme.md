# Mock Symfony App

Mock Symfony app dev env



## Setup Development Environment

- Clone this repo: `git clone git@github.com:SindriaInc/deploy-immutables-azure.git`
- Move into it: `cd deploy-immutables-azure`
- Build local image: `bash build.sh sindriainc/deploy-immutables-azure local`
- Setup env: `cp .env.local .env`
- Setup docker compose: `cp docker-compose.local.yml docker-compose.yml`
- Start environment: `docker-compose up -d`
