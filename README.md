# DigitaLAce

[![Build Status](https://travis-ci.com/CrownKira/digitalace.svg?branch=main)](https://travis-ci.com/CrownKira/digitalace)

## Getting Started

### Installation

1. Install a stable version of NodeJS. The active LTS or current version should work fine.
2. Install Docker.

- macOS and Windows users can install [Docker Desktop](https://www.docker.com/products/docker-desktop) which contains both Docker and Docker-Compose tools.
- Linux users need to follow the instructions on [Get Docker CE for Ubuntu](https://docs.docker.com/install/linux/docker-ce/ubuntu/) and then [Install Docker Compose](https://docs.docker.com/compose/install/) separately.
- You are good to go when you can successfully run:
  `docker-compose --version`

3. Install ModHeader.

- To test our API, we use [Google Chrome](https://www.google.com/chrome/) with the [ModHeader extension](https://chrome.google.com/webstore/detail/modheader/idgpnmonknjnojddfkpgkljpfnnfcklj?hl=en).

4. Run `git clone <repo_url> --recursive` and navigate to it using "cd" in your command line or shell tool.
5. Run `docker compose up` (This will start up all containers).
6. Point your browser to http://localhost:3000 to access the frontend.
7. Point your browser to http://localhost:5000 to access the backend.

## Development

### Docker Containers

1. api (running backend server)
2. db (running postgresql server)
3. client (running frontend server)

### Useful Commands

- `docker exec -it <container> sh`: to access the container
- `docker compose run <container> sh -c "<command>"`: to run the command in the container
- `docker compose run <container>`: to run the container

### Contribution Guidelines

#### As a Collaborator

##### To make a pull request

- `git clone <repo_url> --recursive`
- cd to the project directory
- `git checkout <branch>`
- (make changes)
- `git add .`
- `git commit -m 'commit message'`
- `git push origin <branch>`
- compare and pull request

#### To contribute to a pull request branch

- `git fetch origin pull/<id>/head:<branch>`
- `git checkout <branch>`
- (make changes)
- `git add .`
- `git commit -m 'commit message'`
- `git push origin <branch>`
- compare and pull request
