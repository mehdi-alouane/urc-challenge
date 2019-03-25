# United remote codding challenge
this repo contains united remote challenge, both [backend](https://github.com/mehdi-alouane/urc-backend) and [frontend](https://github.com/mehdi-alouane/urc-frontend)

## Before installation
you need **[git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)** and **[docker](https://docs.docker.com/install/)** installed in your machine

## Installation

first clone the repo

```bash
git clone --recursive git@github.com:mehdi-alouane/urc-challenge.git
```

second start dockerc-compose

```bash
docker-compose build
docker-compose up -d
```

to update submodules, just follow my commande

```bash
git submodule update --init --recursive
```