## Commands

```bash
$ npm i -g @nestjs/cli
$ nest new app
```

```bash
docker build --tag lic-nest-app:v0.3 --file Dockerfile .
docker tag lic-nest-app:v0.3 ghcr.io/developkosarev/lic-nest-app:v0.3
docker images ghcr.io/developkosarev/*
docker push ghcr.io/developkosarev/lic-nest-app:v0.3
docker run -d -p 3000:3000 --name lic-nest-app lic-nest-app:v0.3
```

## Description

[Nest](https://github.com/nestjs/nest) framework TypeScript starter repository.

## Installation

```bash
$ npm install
```

## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

### Useful articles
1. How to push image to **ghcr.io**: [https://docs.github.com/en/packages/working-with-a-github-packages-registry/working-with-the-container-registry](https://docs.github.com/en/packages/working-with-a-github-packages-registry/working-with-the-container-registry)
1. How to reduce the container (size decrease) [https://habr.com/ru/companies/nixys/articles/437372/](https://habr.com/ru/companies/nixys/articles/437372/)
1. Docker compose ansible [https://medium.com/swlh/deploying-docker-compose-applications-with-ansible-and-github-actions-7f1740392507](https://medium.com/swlh/deploying-docker-compose-applications-with-ansible-and-github-actions-7f1740392507)