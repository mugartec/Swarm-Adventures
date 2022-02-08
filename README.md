# Swarm Adventures

![Swarm Adventures](./images/swarm-adventures.jpeg)

*The heat from your computer is not wasted if you need to heat your home.*   - Satoshi Nakamoto

**UNDER DEVELOPMENT**

This repo documents my adventures deploying applications and services to a [Docker Swarm](https://docs.docker.com/engine/swarm/) cluster at home. My intention is both to help the less-experienced and learn from the more-experienced users. So please open an issue if you disagree with some design decisions, find any technical errors, have any questions or simply want to discuss something.

## Table of Contents
 - [Introduction](./sections/intro.md)
   - [Why Swarm?](./sections/intro.md#why-swarm?)
   - [Infrastructure](./sections/intro.md#cluster-infrastructure)
 - [Application architecture](./sections/architecture.md) TBR
   - [Central services](./sections/architecture.md#centralservices) TBR
   - [Overlay networks](./sections/architecture.md#centralservices) TBR
   - [Nextcloud as an example](./sections/architecture.md#centralservices) TBR
 - [Setup](./sections/setup.md) TBR
   - [OS and software](./sections/setup.md#install) TBR
   - [Testing the setup](./sections/setup.md#testing) TBR
   - [NFS for persistent storage](./sections/setup.md#NFS) TBR
 - [Central services](./sections/services.md) TBR
   - [Databases](./sections/services.md#postgres) TBR
   - [Object Store](./sections/services.md#minio) TBR
   - [Reverse Proxy](./sections/setup.md#traefik) TBR
 - [Networking](./sections/networking.md) TBR
   - [Access from the internet](./sections/networking.md#internet) TBR
   - [Testing central services](./sections/networking.md#testing) TBR
 - [Self-hosting Services](./sections/deploy.md) TBR
   - [Installing Portainer](./sections/deploy.md#portainer) TBR
   - [Prerequisites](./sections/deploy.md#prerequisites) TBR
   - [An example application](./sections/deploy.md#example) TBR
