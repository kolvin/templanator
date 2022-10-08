<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
## Contents

- [templator](#templator)
  - [badges](#badges)
  - [Prerequisites](#prerequisites)
  - [Execute Service Commands](#execute-service-commands)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# templator
This repo is used to template other repos

## badges
![go](https://img.shields.io/badge/Go-v1.19-blue)
[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-%23FE5196?logo=conventionalcommits&logoColor=white)](https://conventionalcommits.org) 
[![Semantic Release - angular](https://img.shields.io/static/v1?label=Semantic+Release&message=angular&color=e10079&logo=semantic-release)](https://github.com/semantic-release/semantic-release) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


## Prerequisites
- [Docker](https://docs.docker.com/get-docker/) + [Docker Compose](https://docs.docker.com/compose/install/) are required to run the project
```
cp .env.example .env
docker-compose up -d
```

## Execute Service Commands
```
docker-compose exec <service> <command>

ie: docker-compose exec app npm ...
ie: docker-compose exec app npx ...
ie: docker-compose exec app pnpm ...
```
