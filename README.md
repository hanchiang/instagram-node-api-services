# Introduction

This repository is the centralised repository that contains the services for my instagram API project.
Development work is done using `docker-compose`, and deployed in a kubernetes cluster via GKE.

## Services

- [API server](https://github.com/hanchiang/instagram-node-api)

## Prerequisites

1. Install [git](https://git-scm.com/downloads)
1. Install [docker](https://docs.docker.com/engine/install/)
1. Install [docker compose](https://docs.docker.com/compose/install/)
1. Clone this project: `git clone https://github.com/hanchiang/instagram-node-api-services.git`
1. Clone [API server](https://github.com/hanchiang/instagram-node-api): `git clone https://github.com/hanchiang/instagram-node-api.git backend`

## Usage

- Start API server: `docker-compose up -d backend`
- Visit server at `localhost:3000`
