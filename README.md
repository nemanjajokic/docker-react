# Docker learning project

## Some of the commands

### `docker build -f Dockerfile.dev .`

Build an image for dev env

### `docker build .`

Build an image for prod env

### `docker compose up --build`

Build everything defined in docker-copmose.yml

### `docker run -p 3000:3000 -v /app/node_modules -v $(pwd):/app [Container ID]`

Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page should reload when you make changes.\
It will access code outside of container (Docker volumes)

### `docker compose up`

Run services defined in docker-compose.yml

### `docker run -it [Container ID] npm run test`

Run tests

### `docker run -p 8080:80 [Container ID]`

Run app on nginx

### Deployment

...
