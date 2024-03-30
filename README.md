# Sample Node.js application

This repository is a sample Node.js application for Docker's documentation.


# use compose
docker compose up --build
docker compose down

# use docker
docker build . -f Dockerfile2 --progress=plain --no-cache --build-arg foo=baaaarrrr

# postgres data location
\\wsl.localhost\docker-desktop-data\data\docker\volumes