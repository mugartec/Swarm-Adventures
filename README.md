# Swarm Adventures

![Swarm Adventures](./images/swarm-adventures.jpeg)

> *The heat from your computer is not wasted if you need to heat your home.* - Satoshi Nakamoto

**UNDER DEVELOPMENT. TBW = To Be Written**

I wanted to write a book but didn’t know what to write about. Of course, the book would have to be available for free in a self-hosted website where people could leave reviews and comments, all built on top of open-source tools. But self-hosting this kind of applications the right way is not trivial. So the book is about how I did that 💡. 

This is not supposed to be a guide or a how-to, use it as such at your own risk. This book is simply a journal of my wild adventures deploying a [Docker Swarm](https://docs.docker.com/engine/swarm/) cluster at home to run self-hosted applications in a *decent* way. I'd love to hear what you think about my setup and design decisions, so if you disagree with something, find any technical errors, have any questions or simply want to discuss some points, please open an issue.

English is not my first language, PRs fixing typos or grammar errors are **very** welcome.

## Table of Contents
 - [Introduction](./sections/intro.md)
   - [Why Swarm?](./sections/intro.md#why-swarm)
   - [Infrastructure](./sections/intro.md#cluster-infrastructure)
 - [Application architecture](./sections/architecture.md)
   - [Common services](./sections/architecture.md#common-services)
   - [Persistent data](./sections/architecture.md#persistent-data)
   - [Reverse proxy](./sections/architecture.md#reverse-proxy)
   - [Overlay networks](./sections/architecture.md#overlay-networks)
 - [Setup](./sections/setup.md)
   - [Operating system](./sections/setup.md#operating-system)
   - [Installing Docker](./sections/setup.md#installing-docker)
   - [The Swarm cluster](./sections/setup.md#the-swarm-cluster)
 - [Central services](./sections/services.md) TBW
   - [Database](./sections/services.md#databases) TBW
   - [Object Store](./sections/services.md#object-store) TBW
   - [Reverse Proxy](./sections/setup.md#reverse-proxy) TBW
 - [Self-hosting paradise](./sections/deploy.md) TBW
   - [Prerequisites](./sections/deploy.md#prerequisites) TBW
   - [Let's run some!](./sections/deploy.md#example) TBW

<!-- ## Acknowledgements -->
<!-- I'd like to thank Nico Salas and Felipe Cortés for their infinite patience listening to my low-level (in every way) and not always smart ideas. They are self-hosting adventurers of my own heart 🙌. I'd also like to thank Diego Cathalifaud for his thoughtful comments and suggestions on writing the journal of my adventures. -->
