# Portainer

**IMAGE**

portainer/portainer-ce:latest

## Installation

> CMD: Projektordner erstellen und hinein wechseln

    mkdir Name; cd Name

> CMD: git clone & git remote

    git clone https://github.com/tBrause/docker-portainer.git .; git remote remove origin;

## Startet Portainer

> CMD: docker-compose

    docker-compose up -d

**Container Name**

- con-portainer

**Restart**

- always

**PORTS**

- 9000
- 9443

**Networks**

- portainer-net